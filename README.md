# DSA
## Introduction to the Queue data structure
A queue is an ordered list of elements where an element is inserted at the end of the queue and is removed from the front of the queue.

A queue works based on the first-in, first-out (FIFO) principle, which is different from a stack, which works based on the last-in, first-out (LIFO) principle.

A queue has two main operations:

- Insert a new element at the end of the queue, which is called enqueue.
- Remove an element from the front of the queue, which is called dequeue.
The following picture illustrates a queue:

![Queue-Illustration](/Queue/JavaScript-Queue-Illustration.png)

Another important operation of a queue is getting the element at the front called peek. Different from the dequeue operation, the peek operation returns the element at the front without modifying the queue.

The name queue comes from the analogy to a queue of customers at a bank. The customer who comes first will be served first, and the one who comes later is queued at the end of the queue and will be served later.

![Queue-Illustration2](/Queue/queue-at-a-bank.png)