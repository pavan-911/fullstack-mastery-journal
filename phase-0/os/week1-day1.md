# Week 1 - Day 1: OS Fundamentals
Date: 17-02-2026



What is a Process?
process is defined as 
program gets loaded to the memory and processor executes the program in the memory 
this entire working is defined as process.
processes can be switched by the cpu because of the scheduler
if any malpractice takes place in the particular process it won't get affected to the other process
we can consider chrome tabs as example


What is a Thread?
thread is a small unit in the process
process must contain 1 thread, and that is called main thread
these thread can share data inside the process
if any of the threads gets affected then it leads to the entire malpractice of the process
a process can have no.of threads
these threads can perform simultaneously


Can one process have multiple threads?
yes, once process can have multiple no.of threads
these can perform simultaneously
these are the units of the process


What is Stack memory vs Heap memory?
stack memory
this allocates memory for the local variablles when functions are called
and these also gets deallocated once these complete there function
stack holds limitted space
each local variable must be assigned with data before its function is called
faster

heap memory
this is a dynamic way of allotting memory to the variables
once a function called, it's data gets stored and will not be deallaoted until it is done explicity
heap is somewhat slower when compared to the stack 
can store large amount of data


What does Blocking I/O mean?
while a process is undergoing, suddenly may be paused and other process would be undergoing due to cpu scheduler and waiting for its command to resume the process
Blocking I/O means when a program makes a request (like reading a file or calling an API), it stops and waits doing nothing until the response comes back. Like standing in a queue — you can't do anything else until your turn.
Non-blocking I/O means the program sends the request and continues doing other things while waiting for the response.
