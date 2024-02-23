# CECS 326 Reading Assignment: Introduction to Operating Systems

### Assignment Description
Answer the following questions from the Chapter 1 reading from your text- book. Be through and complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

Andrew Dante (026050685)

1. What are the two main functions of an operating system?

    The two main functions of an operating system is providing application programmers a clean abstract set of resources and managing hardware resources.

2. What is the difference between timesharing and multiprogramming systems?

    The difference between timesharing and multiprogramming system is timesharing has multiple users in individual online terminals all sharing to a CPU that allocates time to multiple small-scale jobs, while multiprogramming systems partition memory in a way so that while one job was waiting for I/O to complete, another jobs could be using the CPU.

3. The family-of-computers idea was introduced in the 1960s with the IBM System/360 mainframes. Is this idea now dead as a doornail or does it live on?

    The family-of-computers idea lives on in the form of computer centers today, often used for managing huge databases or as servers for World Wide Web sites that process thousands of requests per second.

4. What is the difference between kernel and user mode? Explain how having two distinct modes aids in designing an operating system.

    The differences between kernel and user mode is that kernel mode has access to all of the system's hardware and can execute any instrcution it is capable to make, while user mode only have a subset of machine instructions, usually restricted from executing instructions that affect control of the machine. These two aid in designing an operating system in that if a user does not like a particular email reader as is available in user mode, he/she is free to obtain a different one or write a completely new one, while he/she cannot change the clock interrupt handler, which is part of the operating system and heavily protected.

5. On early computers, every byte of data read or written was handled by the CPU (i.e., there was no DMA). What implications does this have for multiprogramming?
    
    The implication with not having a DMA, or something akin to a DMA, makes it longer and resource intensive to multiprogram because transfering bytes from one job to another is a way to facilitate multiprogramming.

6. There are several design goals in building an operating system, for example, resource utilization, timeliness, robustness, and so on. Give an example of two design goals that may contradict one another.

    Two design goals that may contradict each other is resource utilization and robustness, because in order to maximize efficiency, you put resources away from stablizing and making sure things run smoothly. Robustness is not necessarily inefficient, but can present scenario of not doing things "optimally".

7. Which of the following instructions should be allowed only in kernel mode?
    (a) Disable all interrupts.
    (b) Read the time-of-day clock.
    (c) Set the time-of-day clock. (d) Change the memory map.

    Disabling all interrupts, setting the time-of-day clock, and changing the memory map should only be allowed in kernel mode.

8. Consider a system that has two CPUs, each CPU having two threads (hyperthreading). Suppose three programs, P0, P1, and P2, are started with run times of 5, 10 and 20 msec, respectively. How long will it take to complete the execution of these programs? Assume that all three programs are 100% CPU bound, do not block during execution, and do not change CPUs once assigned.

    It will take 20 msec to complete the execution of these programs.

9. What is a trap instruction? Explain its use in operating systems.

    The trap instruction swiches from user mode to kernel mode and starts the operating system, where control is returned to the user program follwing the system call. Most traps are served to warn of an exceptional situation and resolve it, error messsage or not.

10. Modern operating systems decouple a process address space from the machine’s physical memory. List two advantages of this design.

    One advantage to the modern operating systems decoupling a process address space from the machine's physical memory is that it is able to use a process that has a larger address space than the computer's main memory. Another advantage is that the operating system creates the abstraction of an address space as the set of addresses a process may reference.

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.