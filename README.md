# Queue-in-Cpp
# Name: Rajeev Ramesh Reddy E
# PRN: 24070123081

Aim: To implement a Queue data structure using arrays in C++ and perform basic operations such as enqueue, dequeue, and display.

Software Used: Vs Code

Theory:

A queue is a linear data structure that operates on the FIFO (First-In-First-Out) principle. The first element inserted is the first to be removed. It models real-world scenarios like waiting lines or task scheduling.
   Characteristics:
- Insertion happens at the rear using push().
- Deletion happens at the front using pop().
- You can access the front element using front().
- Check if the queue is empty using empty().
   Types of Queues:
- Simple Queue – Basic FIFO structure.
- Circular Queue – Reuses empty space efficiently.
- Priority Queue – Elements are dequeued based on priority.
- Deque (Double-Ended Queue) – Insertion/deletion at both ends.

Algorithm:

Algorithm of the code is:

 Queue Algorithm

 1. Initialize Queue
- Set `front = -1` and `rear = -1` to indicate the queue is empty.

 2. Enqueue Operation
- Check if `rear == SIZE - 1` → If true, print "Queue Overflow!" and exit.
- If `front == -1`, set `front = 0` to start the queue.
- Increment `rear` and insert the value at `arr[rear]`.

 3. Dequeue Operation
- Check if `front == -1` or `front > rear` → If true, print "Queue Underflow!" and exit.
- Print and remove `arr[front]`, then increment `front`.

 4. Display Queue
- If queue is empty (`front == -1` or `front > rear`), print "Queue is empty."
- Else, loop from `front` to `rear` and print each element.

 5. Main Execution
- Create a `Queue` object.
- Call `enqueue()`, `dequeue()`, and `display()` to demonstrate functionality.

Conclusion:

This project successfully demonstrates queue operations using arrays in C++. It highlights FIFO behavior, overflow and underflow handling, and basic object-oriented design. Through practical implementation and structured logic, it reinforces foundational programming concepts and prepares learners for more advanced data structures like circular queues, linked lists, and priority queues.


