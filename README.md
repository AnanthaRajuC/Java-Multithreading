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

## Thread Priorities

Priority of a Java Thread helps the **Operating System** determine the order in which threads are scheduled.

Priority of a thread can be assigned in two ways
- by **JVM** while creating the thread
- by **Programmer** explicitly.

| Priority  | Value  |
|---|---|
|**MIN_PRIORITY**|1|
|**NORM_PRIORITY**|5|
|**MAX_PRIORITY**|10|

- *NORM_PRIORITY: It is the **Default Thread Priority** if the priority of a thread is not explicity mentioned.*
