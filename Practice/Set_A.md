# Java Multithreading Assignment

## Question 1
In what situation is using join(timeout) generally a better choice than using join() without a timeout in Java?

- a. When you need to ensure the strict sequential execution of all threads without any overlap.
- b. When a thread might hang or take too long, and the main thread should continue after a limited waiting period.
- c. When you want the main thread to terminate other threads automatically if they don't finish in time.
- d. When the program must always wait for all threads to finish, no matter how long they take.

*Answer:* b

## Question 2
To retrieve the priority of a thread, you would use the ______ method.

*Answer:* getPriority()

## Question 3
Which method is used to retrieve the name of the current thread?

- a. getName()
- b. getID()
- c. currentThread().getName()
- d. getPriority()

*Answer:* c

## Question 4
True or False: The getName() method is used to get the name of a thread, which is a unique, system-generated identifier.

- a. True
- b. False

*Answer:* b

## Question 5
The getID() method returns a long value that uniquely identifies a thread during its ______.

*Answer:* lifetime

## Question 6
What happens when thread-X calls join() on another thread (thread-Y)?

- a. The calling thread-X continues its execution in parallel with the other thread-Y.
- b. Both threads immediately terminate.
- c. The calling thread-X goes into a waiting state until the thread-Y has completed its run() method.
- d. The thread that thread-X has called join() on is given higher priority by the JVM.

*Answer:* c

## Question 7
Explain the difference between calling the function run() and start() of a thread. Support your answer with a short code example (including the output of both calls).

*Answer:*
- run() executes in the current thread.
- start() creates a new thread and then calls run() internally.

## Question 8
Can a thread call join() on itself?

- a. No, it will not compile.
- b. Yes, and the thread will resume its task after a short delay.
- c. Yes, and it will cause the thread to pause indefinitely.
- d. Yes, and it will cause a deadlock.

*Answer:* d
