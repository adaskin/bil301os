---
title: ammar daskin - Operating Systems (Fall 2025 at Istanbul Medeniyet University)
---

[⟶Lecture Notes](#weekly-topics-and-lecture-notes)



Wednesday  8:30 pm @B501

Basic C and systems programming skills are required: 
*   C Programming,   A little Unix or Linux,   Data Structure and Algorithms    
*  you are expected to have prior programming experience in Linux with C and basic understanding of data structure and algorithms. 

This course introduces students to the concepts of operating systems and provides them with a solid understanding of what operating systems are and what they do and their principles.  This course puts particular emphasis on concurrency and synchronization tools and their implementations.  During the semester, in addition to weekly lectures and lab sessions, there will be programming assignments (mostly in Linux) and in class quizzes. It is crucial for you to follow weekly lectures to learn the material and complete the assignments. 

## Textbooks and Course Material

*   Operating System Concepts, 10th Edition Abraham Silberschatz, Greg Gagne, Peter B. Galvin, [https://www.wiley.com/en-us/Operating+System+Concepts%2C+10th+Edition-p-9781119320913](https://www.wiley.com/en-us/Operating+System+Concepts%2C+10th+Edition-p-9781119320913)
    
* ### Lectures slides are based on the slides 
    
    *   [https://www.scs.stanford.edu/24wi-cs212/notes/](https://www.scs.stanford.edu/24wi-cs212/notes/)         
    *   [https://www.os-book.com/OS10/slide-dir/index.html](https://www.os-book.com/OS10/slide-dir/index.html)         
    *   and [https://linux-kernel-labs.github.io/](https://linux-kernel-labs.github.io/) 
* ### Other resources
    *   [Linux Kernel Documentation](https://www.kernel.org/doc/html/latest/)         
    *   [intel CPU manual](https://www.intel.com/content/www/us/en/developer/articles/technical/intel-sdm.html)         
    *   OS security and more: [https://www.ics.uci.edu/~goodrich/teach/cs201P/notes/](https://www.ics.uci.edu/~goodrich/teach/cs201P/notes/)         
    *   ebook for synchronization [https://dl.acm.org/doi/book/10.5555/2385452](https://dl.acm.org/doi/book/10.5555/2385452)         
        *   [https://booksite.elsevier.com/9780123973375/](https://booksite.elsevier.com/9780123973375/)            
    *   [kernel source code](https://elixir.bootlin.com/linux/latest/source/kernel)        
    *   [https://linux-kernel-labs.github.io/refs/heads/master/index.html](https://linux-kernel-labs.github.io/refs/heads/master/index.html)         
    *   Testing Linux: [https://linux-test-project.github.io/](https://linux-test-project.github.io/)
        
## Weekly topics and lecture notes
* Week-1:
  1. Administrivia [⟶0administrivia.pdf](lectures/0administrivia.pdf)
  2. Intro: running a software on a machine [⟶0intro-os-vms-running-sw.pdf](lectures/0intro-os-vms-running-sw.pdf)
     1. An extra: How to interact with OS: some terminal commands [⟶0intro-how-to-interact-with-os](lectures/0intro-how-to-interact-with-os)
  3. Chapter 1: Introduction to OS  [⟶1intro.pdf](lectures/1intro.pdf) 

2. Chapter 2: Operating System Services-structures-linkers/loaders  [⟶2services-structs.pdf](lectures/2services-structs.pdf) 
3. Chapter 3: Processes     [⟶3processes.pdf](lectures/3processes.pdf) 
4. Chapter 4: Threads & Concurrency   [⟶4concurrency-threads.pdf](lectures/4concurrency-threads.pdf)   
5. Chapter 5: CPU Scheduling    [⟶5cpu-scheduling.pdf](lectures/5cpu-scheduling.pdf) 
   - some readings: 
     - [Old CFS load balancing issues on multicore](https://people.ece.ubc.ca/sasha/papers/eurosys16-final29.pdf)
     - [New Linux Scheduler](https://docs.kernel.org/scheduler/sched-eevdf.html)
6. Intro to Synchronization: Peterson solution, spin-locks, atomic instructions, memory barriers (e.g., mb, fence, volatile), C11 atomic library (relaxed, acquire, release) 
    [⟶6synchronization-intro.pdf](lectures/6synchronization-intro.pdf) 
7.  Midterm exam 
8.  Synchronization II (implementation of locks, low level locks: disabling interrupts and spin-locks, improving spinlock efficiency, lock free programming, cache coherency, deadlock, transactional memory)    
    [⟶7synchronization-II.pdf](lectures/7synchronization-II.pdf)  
9.  Synchronization review  
    [⟶8synchronization-review.pdf](lectures/8synchronization-review.pdf)  
10.  Chapter 9: Main Memory  
    [⟶9vm-hw.pdf](lectures/9vm-hw.pdf)  
11.  Chapter 10: Virtual Memory    
    [⟶10vm-os.pdf](lectures/10vm-os.pdf) 
12.  Chapter 11-12: I/O Systems   
    [⟶11io-systems.pdf](lectures/11io-systems.pdf) 
13. Disk and storage
    [⟶12disk-io.pdf](lectures/12disk-io.pdf)   
14.  Chapter 13-14-15: File-System Interface, Implementation, and Internals    
    [⟶13file-systems.pdf](lectures/13file-systems.pdf)   
15.  Protection, Security
    [⟶14protection-security.pdf](lectures/14protection-security.pdf)  
    

## Homeworks and exams
*   Assigned via classroom.google.com or from github    
*   4-5 HWs **(not mandatory)**: includes programming assignments that may require compiling and configuring Linux-kernel, adding system calls to kernel that reads kernel structures and copies this info to user programs, changing kernel parameters or programs, adding new modules, /proc file system, and device drivers    
*   No late submission    
*   Submissions through classroom.google.com
*   1-midterm    
*   1-final
  
## Grading      
*   40% midterm exam    
*   60% final exam
    
## Discussions
For the assignment submission/grading and discussions, we will use [https://classroom.google.com](https://classroom.google.com/) and for public discussions, we will use [https://piazza.com](https://piazza.com/) for this course.  In discussions and questions:

*   Do not post solutions or any significant part of an assignment.    
*   Do not post anything not related to the course.    
*   Ask a question when you would like some help with something    
*   Post something when you would like to help others with something.
    

## Collaboration and Cheating Policy
*   Any kind of plagiarism and cheating are prohibited (Please, refer to the university cheating policy).    
*   If you benefit from some work of others, list them as references (online references or books)     
*   Discussing the assignments or projects with your friends is allowed; but, all the submitted work should be yours alone. List your collaborators (if you discuss your homework with your friends) in your assignments.