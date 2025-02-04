# threading

𝐉𝐚𝐯𝐚 🚀 
1. Concurrency Series By Baeldung: https://lnkd.in/gBtMG6Mk

2. Proving Concurrency Requirement: https://lnkd.in/gwvvBWxY

3. Concurrency Series by Jenkov: https://lnkd.in/gaWZUj3W


𝐆𝐨 🚀 

1. Utlimate Concurreny Guide on Github: https://lnkd.in/gRU-Z-WS
2. Concurrency Patterns: https://lnkd.in/g6nq6ZRP

If you want to build real systems like Redis, Kafka, DNS and a SqlLite Database yourself checkout these best of a kind tutorials.

1. Build Your Own Redis: https://lnkd.in/gz92ygFH
2. Build Your Own Kafka: https://lnkd.in/gm58s8CX
3. Build Your Own Http Server: https://lnkd.in/g_VxvcUN
4. Build Your Own DNS Server: https://lnkd.in/g7iM2F69

Plus amazing tutorials for all languages like Go, Rust, Java and Python.

Bonus:
Lock Free Algorithms: 
1. https://lnkd.in/gTwk6Cpk
2. https://lnkd.in/gYVSVska

7 Multithreading Design Patterns

 Background -
◾ Multithreading is a computational model that enables a single program (process) to execute multiple tasks concurrently.
◾ These tasks are called threads, lightweight units of execution that share the same process resources (memory space, open files, etc.).
◾ While multithreading offers tremendous potential for performance gains and responsive applications, it also introduces complexities like synchronization, communication and potential race conditions.
◾ Multithreading design patterns are reusable solutions that address such common challenges.

📌 Let's learn the design patterns.

[1.] Producer-Consumer Pattern
◾ This pattern involves two types of threads: producers, which generate data, and consumers, which process that data.
◾ A shared queue acts as a buffer between the two.

When to use?
◾ When tasks can be divided into distinct stages of production and consumption, and you want to decouple these stages for improved concurrency and efficiency.

[2.] Thread Pool Pattern
◾ Maintains a pool of worker threads that can be reused for executing tasks.
◾ It avoids the overhead of creating and destroying threads for each task.

When to use?
◾ When you have a large number of short-lived tasks and want to manage the number of threads for better resource utilization and performance.

[3.] Futures and Promises Pattern
◾ Represents the result of an asynchronous operation.
◾ The promise is an object that holds the eventual result and the future provides a way to access that result when it becomes available.

When to use?
◾ When dealing with long-running operations that you want to execute concurrently without blocking the main thread.

[4.] Monitor Object Pattern
◾ Provides a mechanism for synchronizing access to shared resources.
◾ It allows only one thread to execute a critical section of code at a time, preventing race conditions.

When to use?
◾ When you need to protect shared data or resources from concurrent access and ensure thread safety.

[5.] Read-Write Lock Pattern
◾ Allows multiple threads to read from a shared resource concurrently but allows only one thread to write to it at a time.

When to use?
◾ When you have a shared resource where reads are more frequent than writes, and you want to optimize for read concurrency.

[6.] Barrier Pattern
◾ Synchronizes a group of threads to wait at a common point before proceeding further.

When to use?
◾ When you have parallel tasks that need to complete a specific stage before moving on to the next stage.

[7.] Active Object Pattern
◾ Decouples method execution from method invocation for concurrent systems.
◾ It involves an object with its own thread of control and a scheduler to queue and execute method requests.

When to use?
◾ When you want to encapsulate the thread management and scheduling logic within an object, providing a cleaner interface for concurrent operations.

