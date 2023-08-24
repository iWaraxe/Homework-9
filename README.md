# Homework Assignment: Exploring Multithreading in Java
Objective:
To explore and understand the concepts of multithreading in Java through hands-on programming exercises.

## Task 1: Simple Thread Creation
Create a class that extends the Thread class.
Override the run method to print a message.
Create an instance of your class and call the start method to execute the thread.
Observe how the thread executes concurrently with the main thread.

## Task 2: Implementing Runnable Interface
Create a class that implements the Runnable interface.
Implement the run method to print a message.
Create a Thread object, passing your class instance to it, and call start.
Compare this approach with Task 1 and write a brief explanation of the differences.

## Task 3: Synchronization
Create a shared resource class that has a synchronized method.
Create multiple threads that access this shared resource.
Demonstrate how synchronization ensures that the shared resource is accessed by one thread at a time.
Experiment by removing synchronization and observe what happens.

## Task 4: Inter-thread Communication (Producer-Consumer Problem)
Create two classes, Producer and Consumer, that share a common data storage class.
Use wait() and notify() to ensure that the Producer waits if the storage is full, and the Consumer waits if the storage is empty.
Demonstrate how the Producer and Consumer can work concurrently without conflict.

## Task 5: Reflection
Write a one-page reflection on:
What you've learned about threads and multithreading in Java?
The challenges you faced and how you overcame them?
How you can apply multithreading in real-world applications?

## Submission:
Submit all your code files along with the reflection document.
Ensure that your code is well-commented, explaining what each part does.