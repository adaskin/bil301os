---
title: ammar daskin - Operating Systems (Fall 2024 at Istanbul Medeniyet University)
---

[⟶Lecture Notes](#weekly-topics-and-lecture-notes)



Monday  1:30 pm @B501

Basic C and systems programming skills are required: 
*   BIL 121 C Programming,      
*   BIL 222 System Programming in Linux,      
*   BIL 201 Data Structure and Algorithms    
*  you are expected to have prior system programming experience in Linux with C and basic understanding of data structure and algorithms. 

This course introduces students to the concepts of operating systems and provides them with a solid understanding of what operating systems are and what they do and their principles.  This course puts particular emphasis on concurrency and synchronization tools and their implementations.  During the semester, in addition to weekly lectures and lab sessions, there will be programming assignments (mostly in Linux) and in class quizzes. It is crucial for you to follow weekly lectures to learn the material and complete the assignments. 

## Textbooks and Course Material

*   Operating System Concepts, 10th Edition Abraham Silberschatz, Greg Gagne, Peter B. Galvin, [https://www.wiley.com/en-us/Operating+System+Concepts%2C+10th+Edition-p-9781119320913](https://www.wiley.com/en-us/Operating+System+Concepts%2C+10th+Edition-p-9781119320913)
    
* ### Lectures slides are based on the slides 
    
    *   [https://www.scs.stanford.edu/24wi-cs212/notes/](https://www.scs.stanford.edu/24wi-cs212/notes/)         
    *   [https://www.os-book.com/OS10/slide-dir/index.html](https://www.os-book.com/OS10/slide-dir/index.html)         
    *   and [https://linux-kernel-labs.github.io/](https://linux-kernel-labs.github.io/) 
        
    *   weekly posted on classroom.google.com before the lecture.         
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
1. Chapter 1: Introduction  [⟶1intro.pdf](lectures/1intro.pdf) 
2. Chapter 2: Operating System Services-structures-linkers/loaders  [⟶2services-structs.pdf](lectures/2services-structs.pdf) 
3. Chapter 3: Processes     [⟶3processes.pdf](lectures/3processes.pdf) 
4. Chapter 4: Threads & Concurrency   [⟶4concurrency-threads.pdf](lectures/4concurrency-threads.pdf)   
5. Chapter 5: CPU Scheduling    [⟶5cpu-scheduling.pdf](lectures/5cpu-scheduling.pdf) 
   - some readings: 
     - [Old CFS load balancing issues on multicore](https://people.ece.ubc.ca/sasha/papers/eurosys16-final29.pdf)
     - [New Linux Scheduler](https://docs.kernel.org/scheduler/sched-eevdf.html)
6. Chapter 5, 6-7: CPU Scheduling\-II, Intro to Synchronization Tools & Examples    
7.  (not included in the book) Synchronization II (atomic instructions, memory barriers (e.g., mb, fence, volatile), C11 atomic library (relaxed, acquire, release), lock free programming, cache coherency,)    
8.  Midterm exam    
9.  Synchronization review, Deadlocks    
10.  Chapter 9: Main Memory    
11.  Chapter 10: Virtual Memory    
12.  Chapter 11-12: I/O Systems    
13.  Chapter 12\-13-14-15: File-System Interface, Implementation, and Internals    
14.  Protection, Security
    

## Homeworks and exams
*   Assigned via classroom.google.com      
*   4-5 HWs: includes programming assignments that may require compiling and configuring Linux-kernel, adding system calls to kernel that reads kernel structures and copies this info to user programs, changing kernel parameters or programs, adding new modules, /proc file system, and device drivers    
*   No late submission    
*   Submissions through classroom.google.com
*   1-midterm    
*   1-final
  
## Grading  
*   30% homework    
*   30% midterm exam    
*   40% final exam
    
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