---
permalink: /LINKS/
---

[The OS Dev Wiki]: https://wiki.osdev.org/

[Makefile Tutorial]: https://makefiletutorial.com/
[The GNU Privacy Handbook]: https://www.gnupg.org/gph/en/manual.html
[Man in the Middle (MITM) Attack]: https://www.veracode.com/security/man-middle-attack

[The basics of file systems]: https://www.ufsexplorer.com/articles/file-systems-basics/
[Linux Directory Structure - GeeksForGeeks]: https://www.geeksforgeeks.org/linux-directory-structure/
[FUSE -- The Linux Kernel documentation]: https://www.kernel.org/doc/html/latest/filesystems/fuse.html
[Develop your own file system with FUSE]: https://developer.ibm.com/articles/l-fuse/

[Paging - OS Dev Wiki]: https://wiki.osdev.org/Paging
[The Memory and Pointers]: http://www.cs.ecu.edu/karl/2530/fall17/Notes/lec20A.html
[Shared Libraries]: https://tldp.org/HOWTO/Program-Library-HOWTO/shared-libraries.html

[virtual memory]: https://www.techtarget.com/searchstorage/definition/virtual-memory
[Memory Allocation]: https://binaryterms.com/static-and-dynamic-memory-allocation.html
[Page Frame Allocation - OS Dev Wiki]: https://wiki.osdev.org/Page_Frame_Allocation

[Processes and Threads]: https://www.d.umn.edu/~gshute/os/processes-and-threads.xhtml
[Concurrency vs. Parallelism -- A brief view]: https://medium.com/@itIsMadhavan/concurrency-vs-parallelism-a-brief-review-b337c8dac350
[Multithreaded Programming Guide]: https://docs.oracle.com/cd/E18752_01/html/816-5137/docinfo.html
[Scheduling Algorithms]: https://wiki.osdev.org/Scheduling_Algorithms

[Process Synchronization: Critical Section Problem in OS]: https://www.guru99.com/process-synchronization.html
[Spinlock]: https://wiki.osdev.org/Spinlock
[Mutex lock for Linux Thread Synchronization]: https://www.geeksforgeeks.org/mutex-lock-for-linux-thread-synchronization/

[Linux From Scratch 11.2]: https://www.linuxfromscratch.org/lfs/view/11.2/
[Scheduling in OS]: https://binaryterms.com/scheduling-in-operating-system.html
[Toolchains]: https://elinux.org/Toolchains 

# LINKS

## Week 01

1. [The OS Dev Wiki] <br>
This is a pretty good link if you're looking to build an operating systems from scratch. The pages here have a pretty hands-on way of explaining certain topics. It is also a good link if you're looking to truly dive deep into operating systems as it covers many aspects of an operating systems and various architectures in great detail. Overall, a great general reference for this course in my opinion.

## Week 02

1. [Makefile Tutorial] <br>
Makefiles are commonly used build tooling. It is used to manage and decide parts of a program to be built/compiled. This tutorial provides a pretty good base for understanding how Makefiles work and the many things we can do with Makefiles. 

2. [The GNU Privacy Handbook] <br>
GnuPG is a tool used for digital encryption that provides a way to do secure communication based on the OpenPGP standard. This handbook provides a comprehensive explanation on the concepts behind GnuPG, various encryption methods, and how to use GnuPG. It also provides good examples so that we can follow along. This helped me gain a more solid base on GnuPG's aims and design.

3. [Man in the Middle (MITM) Attack] <br>
MITM attacks are one of the many ways malicious actor can violate security policies and gain access to resources and data illegitimately. This is a great article that explains how MITM attacks are typically done, key concepts, examples, and several mitigation techniques on dealing with MITM. This helped me gain the fundamentals and overview of MITM attacks.

## Week 03

1. [The basics of file systems]<br>
If you're new to file systems and don't really know how files are stored, this is a good place to start. It provides an overview on file systems and some of the key terms that we will see often. The article also explains about various file systems in different operating systems such as BSD, Solaris, Unix, Linux, Windows, and macOS.

2. [Linux Directory Structure - GeeksForGeeks]<br>
This article explains about the structure of the Linux directory and file system. It covers information about various directories and files as well as their purpose, ranging from kernel files, device files, configuration files, etc. Whatever file/directory you want to know about, this article is a great place to get started.

3. [FUSE -- The Linux Kernel documentation]<br>
What better way to understand FUSE in the Linux file system other than by reading its kernel documentation directly? Yes, the Linux kernel documentation provides an entire section on FUSE. It covers key terms, definitions, commands/options, and examples on how FUSE is used in Linux. This is a good read if you want to know more about FUSE and how it works in Linux.

4. [Develop your own file system with FUSE]<br>
If you want to get a bit more deep and hands-on with FUSE, this article might be for you. This article gives a comprehensive breakdown on implementing our own file system with FUSE. It also covers several components of the FUSE library and APIs. Not exactly an easy read, but certainly a great one.

# Week 04

1. [Paging - OS Dev Wiki]<br>
I've talked about the OS Dev wiki multiple times already because it's such a great learning resource. This section of the wiki thoroughly explains about paging, the benefits, implementations, page faults, and more. Paging is a pretty difficult thing to implement and this wiki is here to help.

2. [The Memory and Pointers]<br>
Pointers are such a core concept in many different fields of programming, not just for operating systems. Knowing how to handle and use pointers correctly can go a long way. This article gives a great explanation and examples of pointers and computer memory.

3. [Shared Libraries]<br>
Shared libraries allows pre-compiled code to be used and shared by different programs that need it. This article explains pretty well about shared libraries from a more hands-on perspective.

# Week 05

1. [virtual memory]<br>
This article provides a great high-level view on virtual memory. It explains about what it is, how it works, the types out there, how to manage it, etc. It's a great starter and reference point for beginners and those who already know virtual memory.

2. [Memory Allocation]<br>
This article explains memory allocation in a simple and concise way. It focuses on the types of memory allocation and its pros and cons. It even has a key takeaways section that summarizes all key points of the article.

3. [Page Frame Allocation - OS Dev Wiki]<br>
The OS Dev Wiki has made multiple appearances in my links and I can't really blame them. This section of the wiki provides explanations on physical and and virtual memory allocations and the various approach and data structures involved. In my opinion, this highly compliments the textbook presentation on Page Frames.

# Week 06

1. [Processes and Threads]<br>
Understanding what processes, programs, and threads are is an important part of becoming a better programmer in general. It helps in understanding how computers are able to do the things they can do and how they do it. This simple page provides a nice introduction to the topic.

2. [Concurrency vs. Parallelism -- A brief view]<br>
To be able to optimize resource usage and performance, operating systems and applications in general use the concept of concurrency and parallelism to do this. This article provides a nice foundation in understanding what these two things are and how they affect the scheduling of processes by an operating system.

3. [Multithreaded Programming Guide]<br>
This document provides a comprehensive guide on multithreaded programming from the basic concepts up to the implementation using the pthreads library and other APIs. A bit dense in terms of contents but nevertheless great.

4. [Scheduling Algorithms]<br>
Another wonderful appearance from the OS Dev Wiki. This page explains in detail about the various scheduling algorithms out there used in process scheduling and its pros and cons. I'd recommend this to anyone who wants to know more about process scheduling and the ways it can be done.

# Week 07

1. [Process Synchronization: Critical Section Problem in OS]<br>
This is a neat article to complement our textbook in understanding the critical section problem.

2. [Spinlock]<br>
The OS Dev Wiki never ceases to amaze. This article provides a brief overview on spinlocks as well as some pseudocode in spinlock variations. Another neat article to complement the textbook

3. [Mutex lock for Linux Thread Synchronization]<br>
This article shows how mutexes can be used for thread synchronization. The implementation is made in C but could very well apply to other languages too. Pretty neat read.

# Week 08

1. [Linux From Scratch 11.2]<br>
The official book/guide for Linux From Scratch. This is a clearly written guide which takes us step by step info building LFS. Sometimes the official guide is the best.

2. [Scheduling in OS]<br>
This is a pretty good complementary article to support the current text book on scheduling. It gives a clear and concise explanation about scheduling in general.

3. [Toolchains]<br>
The term toolchain was thrown a lot in the LFS guide. This article helps in giving a brief explanation on what toolchains are and its components.
