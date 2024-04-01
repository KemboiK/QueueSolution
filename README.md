# QueueSolution
## Queue Using Array Example
This Java program demonstrates the implementation of a queue using an array. The code consists of two classes: QueueUsingArray and QueueSolution.

### QueueUsingArray Class
The QueueUsingArray class represents a basic implementation of a queue data structure using an array. Here are the key features of this class:

#### Variables:
front_Q and rear_Q: Track the front and rear positions of the queue.
capacityOfQueue: Represents the maximum capacity of the queue.
q1: Static array to store queue elements.

#### Constructor:
QueueUsingArray(int size): Initializes the queue with the specified size.

#### Methods:
enqueue(int value): Adds an element to the rear of the queue.
dequeue(): Removes an element from the front of the queue.
display(): Displays the elements of the queue.

### QueueSolution Class
The QueueSolution class contains the main method to demonstrate the functionality of the QueueUsingArray class. It performs the following operations:
Creates a queue object q2 with a capacity of 5 using QueueUsingArray constructor.
Enqueues elements (2, 4, 8) into the queue using the enqueue method.
Displays the elements of the queue using the display method.
Dequeues an element from the queue using the dequeue method.
Displays the updated queue after dequeuing.
## How to Use
1.Compile the Java files using a Java compiler (javac).
javac QueueUsingArray.java QueueSolution.java
2.Run the compiled Java program (java) with the QueueSolution class as the entry point.
java QueueSolution
# Notes
Ensure that you provide valid inputs when enqueueing elements to avoid exceeding the queue's capacity.
The dequeue operation removes elements in a FIFO (First-In-First-Out) manner.
