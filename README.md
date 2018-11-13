# Multithreading In Java
Multithreading in java is a process of executing multiple threads simultaneously. A thread is a lightweight sub-process, the smallest unit of processing. These threads can run concurrently. Multiprocessing and multithreading, both are used to achieve multitasking.

# Table of Contents

<!--ts--> 
  * [Life Cycle of a Thread](#life-cycle-of-a-thread)
  * [Thread Priorities](#thread-priorities)
<!--te-->

Threads can be created by using two mechanisms:
1. Extending the Thread class
2. Implementing the Runnable Interface

## Life Cycle of a Thread

| Life Cycle Stage  | Description  |
|---|---|
| **NEW** | newly created thread that has not yet started the execution  |
|**RUNNABLE**|either running or ready for execution but it’s waiting for resource allocation|
|**BLOCKED**|waiting to acquire a monitor lock to enter or re-enter a synchronized block/method|
|**WAITING**|waiting for some other thread to perform a particular action without any time limit|
|**TIMED_WAITING**|waiting for some other thread to perform a specific action for a specified period|
|**TERMINATED**|has completed its execution|

![Thread Life Cycle](resources/images/Life_cycle_of_a_Thread_in_Java.jpg?raw=true "Thread Life Cycle")
