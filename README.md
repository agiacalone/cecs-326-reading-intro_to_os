# CECS 326 Reading Assignment: Introduction to Operating Systems

### Assignment Description
Answer the following questions from the Chapter 1 reading from your text- book. Be through and complete with your answers. You may work on these questions with one or two other partners, but *all* students must submit the document individually in their own repositories along with each student's name documented with the submission.

1. What are the two main functions of an operating system?

2. What is the difference between timesharing and multiprogramming systems?

3. The family-of-computers idea was introduced in the 1960s with the IBM System/360 mainframes. Is this idea now dead as a doornail or does it live on?

4. What is the difference between kernel and user mode? Explain how having two distinct modes aids in designing an operating system.

5. On early computers, every byte of data read or written was handled by the CPU (i.e., there was no DMA). What implications does this have for multiprogramming?

6. There are several design goals in building an operating system, for example, resource utilization, timeliness, robustness, and so on. Give an example of two design goals that may contradict one another.

7. Which of the following instructions should be allowed only in kernel mode?
    (a) Disable all interrupts.
    (b) Read the time-of-day clock.
    (c) Set the time-of-day clock. (d) Change the memory map.

8. Consider a system that has two CPUs, each CPU having two threads (hyperthreading). Suppose three programs, P0, P1, and P2, are started with run times of 5, 10 and 20 msec, respectively. How long will it take to complete the execution of these programs? Assume that all three programs are 100% CPU bound, do not block during execution, and do not change CPUs once assigned.

9. What is a trap instruction? Explain its use in operating systems.

10. Modern operating systems decouple a process address space from the machine’s physical memory. List two advantages of this design.

### Deliverables
* Your writeup file *must* be done in [Markdown](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) format and must be included in the repository as a separate file. View the file [`README.md`](README.md?plain=1) for an example of Markdown.
* Any included images or screenshots should be done in `*.jpg`, `*.png`, or `*.gif` formats, and be included individually as files in your repository (i.e. no binary ‘document’ with the images pasted inside).
* Screenshots or images *may* be linked in your Markdown file writeup if you wish to do so.