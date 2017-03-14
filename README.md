# tauseefTalks
personal blog for my developer story, other interests.

Site published using GitHub pages at - https://curioustauseef.github.io/tauseefTalks/


items to develop
photos
favorite quotes and my understanding of it
favorite books/fiction/novels
technical books i read/ on my bucket list
rules i follow 
question i raise
conversations between prophets and devil
when can humans punish and when is it best left for almighty to punish
when to defend a religuos book and when best left for the book to defend


Cool projects I came across : 

1. Improving the quality of scans of handwritten notes : https://mzucker.github.io/2016/09/20/noteshrink.html
2.http://themes.jekyllrc.org/icard-resume/
3. https://github.com/curiousTauseef/procedural-time-travel-game



Blog Ideas on GitHub : 

1. https://github.com/mzucker/mzucker.github.io
2. must see : https://github.com/shekkbuilder/neko250.github.io
3. folders for content of different years : https://github.com/curiousTauseef/allenzyoung.github.io
4. https://github.com/ldaochen/front-end-handbook-2017

Material : 
1. https://github.com/curiousTauseef/pdfs






Debugging Experience:

1. Using Data Display Debugger(DDD) : use a faulty Seg Fault program to illustrate
2. Using Python debugger : https://pythonconquerstheuniverse.wordpress.com/2009/09/10/debugging-in-python/
3. From blogs : 
                -http://www.brendangregg.com/blog/2016-08-09/gdb-example-ncurses.html
https://github.com/cyrus-and/gdb-dashboard
https://github.com/hugsy/gef

4. Reverse engineering : 
https://github.com/curiousTauseef/prof


Everything about C to ISA :


Everything about memory : 

-http://tldp.org/LDP/tlk/mm/memory.html


1. https://superuser.com/questions/446395/is-it-the-address-bus-size-or-the-data-bus-size-that-determines-8-bit-16-bit
    Generally the size of the databus is determined by the the size of the processor registers. 
    Often it is the size of the processor registers that determine the OS type (64 vs 32).

2. https://www.extremetech.com/extreme/188776-how-l1-and-l2-cpu-caches-work-and-why-theyre-an-essential-part-of-modern-chips

3. http://stackoverflow.com/questions/40330056/why-are-datatypes-self-aligned

4. https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/3/html/Introduction_to_System_Administration/s1-memory-virt-details.html

5. http://stackoverflow.com/questions/9929755/do-multi-core-cpus-share-the-mmu-and-page-tables

6. http://stackoverflow.com/questions/6716946/why-do-64-bit-systems-have-only-a-48-bit-address-space
   On doing cat /proc/cpuinfo I see address sizes	: 36 bits physical, 48 bits virtual. hence the curiosity
   So CPU manufacturers took a shortcut. They use an instruction set which allows a full 64-bit address space, 
   but current CPUs just only use the lower 48 bits. The alternative was wasting transistors on handling a bigger address space which wasn't going to be needed for many years.


7. http://stackoverflow.com/questions/18431261/how-does-x86-paging-work
Logical addresses are the memory addresses used in "regular" user-land code (e.g. the contents of rsi in mov eax, [rsi]).

8. http://stackoverflow.com/questions/10844871/how-can-the-same-linux-program-load-memory-addresses-be-used-multiple-times-on-d?noredirect=1&lq=1
The answer is that each process has its own page tables. They are switched when processes are switched.
It's also worth noting that, fundamentally, "virtual memory" is a "hardware thing". Yes, the OS manages the page tables. But the actual mapping of a virtual address to a physical address is ultimately done by the system's VMM hardware, not by the OS. Hence, from the software's perspective, a "virtual address" (which, in theory, can map to a different physical address at any time) is as "real as it gets".
stil to udnerstand

9. http://stackoverflow.com/questions/26368706/cpu-registers-width-and-memory-addressing-32-bit-or-64-bit
stil to udnerstand

10. http://stackoverflow.com/questions/18431261/how-does-x86-paging-work
Git hub link to bare metal example

11. http://stackoverflow.com/questions/1865501/c-program-on-linux-to-exhaust-memory

12. https://littleosbook.github.io/#getting-to-c

When using a struct to represent configuration bytes, it is very important that the compiler does not add any padding, because the struct will eventually be treated as a 32 bit unsigned integer by the hardware. The attribute packed can be used to force GCC to not add any padding:

13. http://stackoverflow.com/questions/9929755/do-multi-core-cpus-share-the-mmu-and-page-tables
existence of the Translation Lookaside Buffer (TLB), which is the MMU's way of converting the virtual addresses used by a process to a physical memory address.
there is a single MMU per physical processor, at least in SMP systems, so all cores share a single MMU.

http://www.cspray.net/my.so-archive/100-most-influential-programming-books.html

14. http://stackoverflow.com/questions/4743260/how-to-split-program-to-fully-utilize-multi-cpu-multi-core-and-hyper-threading?rq=1



About addressing : 
1. http://tuxthink.blogspot.be/2013/09/to-find-if-cpu-is-32bit-or-64-bit-in.html



Books
Computer Systems a Programmers perspective hallaron
https://github.com/jlroo/Computer-Systems
https://github.com/curiousTauseef/csapp2e-1
https://github.com/curiousTauseef/csapp-1
https://github.com/ldaochen/CSAPP/tree/master/labs

GCC, Porting

1. The Definitive Guide to GCC-By William von Hagen
2. http://ww1.microchip.com/downloads/en/DeviceDoc/50002184B.pdf
3. http://www.nxp.com/assets/documents/data/en/white-papers/CWPORTINGWP.pdf
4. https://developers.slashdot.org/story/15/12/07/2256251/developing-in-cc-why-you-should-consider-clang-over-gcc
5. https://www.ibm.com/developerworks/library/l-port-linux-on-x86-application/



Cloud Computing : 
1. Cloud Computing (The MIT Press Essential Knowledge series) Paperback – by Nayan B. Ruparelia 

-------------------------------------------------
Noteworty programming vibes : 

1. https://jeffknupp.com/blog/2012/03/31/pythons-hardest-problem/
2. https://locklessinc.com/articles/instruction_wishlist/
3. https://danluu.com/new-cpu-features/

Vim Ideas : 

1. How Vim can run the make file : https://www.cs.oberlin.edu/~kuperman/help/vim/etc.html
   http://tilvim.com/2014/03/13/dispatch.html

2. 


C Interview Questions : 
1. http://kundansingh.com/interview/

LinkedList Reading in General : 

LinkedList in Linux
1. http://tuxthink.blogspot.be/2014/02/creating-linked-list-in-liinux-kernel.html

On FlipFlops : 

1. https://www.quora.com/What-is-the-significance-of-D-flip-flop-if-its-output-input-are-same-eventually
2. https://www.quora.com/What-should-I-learn-now-so-that-I-can-call-myself-an-embedded-systems-expert-after-a-year
3. http://spectrum.ieee.org/computing/hardware/the-surprising-story-of-the-first-microprocessors


Experiments to do in free time : 
1. http://jhshi.me/2013/12/13/simulate-random-mac-protocol-in-ns2-part-i/
2. http://jhshi.me/2016/03/09/zathura-pdf-viewer-for-vim-lovers/index.html
3. http://tuxthink.blogspot.be/2014/05/seperating-pdf-into-single-pages-using.html
4. quiz on semaphore, with a score calculation : http://tuxthink.blogspot.be/2014/01/linux-quiz-on-semaphores.html
5. http://tuxthink.blogspot.be/2010/11/writing-example-driver-from-scratch.html
6. http://tuxthink.blogspot.be/2013/07/difference-between-semaphores-and.html
7. http://tuxthink.blogspot.be/2016/12/close-application-cleanly-from-command.html
8. http://jhshi.me/2014/07/11/print-uint64-t-properly-in-c/index.html
9. OS course : https://www.ops-class.org/asst/1/
10. self-mutating program - https://shanetully.com/2013/12/writing-a-self-mutating-x86_64-c-program/
11. Change in CPU after 80s : https://danluu.com/new-cpu-features/
12. http://invisiblethingslab.com/itl/Resources.html
   https://software.intel.com/en-us/blogs/2012/09/25/how-to-enable-an-intel-trusted-execution-technology-capable-server

13. Nanyang TU articles :
    https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html
	https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html

14. Code snippet to find size of structure in kernel code : 
https://scaryreasoner.wordpress.com/2009/07/02/an-interesting-way-to-find-the-size-of-a-structure-in-c/

15. Learning C++
https://scaryreasoner.wordpress.com/2008/07/04/learning-c/

16. Producer Consumer example using kthreads : 
http://www.cs.ucsb.edu/~rich/class/cs170/notes/Kthreads/




Understanding ISA by doing C programs in ISA, :
1. http://pulsar.webshaker.net/2011/04/01/begin-programming-assembler-with-gcc/



understanding summary from
books
short books
papers


linked list and c

linked list in linux



why certain keywords

inline assembly
typedefing
mixing c and assembly : 
https://24alpha.wordpress.com/2007/12/18/how-to-get-gcc-to-interleave-assembly-output-with-original-source-code/


Resource on mutual exclusion by locking, semaphores, spinlocks : 
1. http://www.linuxjournal.com/article/5833
2. https://kernel.readthedocs.io/en/sphinx-samples/kernel-locking.html
3. https://www.kernel.org/pub/linux/kernel/people/rusty/kernel-locking/c214.html
4. https://scaryreasoner.wordpress.com/2013/05/30/may-30-2013-my-current-understanding-of-spin-locks-and-interrupt-handlers-in-the-linux-kernel/
5. https://lwn.net/Articles/146861/
6. https://www.csee.umbc.edu/~jtang/archives/cs421.s16/lectures/L20KernelSynchronizations.pdf






Linux deep diving : 
1. https://scaryreasoner.wordpress.com/2013/09/14/the-life-of-io-in-the-linux-kernel/



Feature (Os technique) - Implemented in C using
Mutual exclusion - inline functions (http://www.aakarshn.com/posts/linux-sync)
kthreads - function pointers (https://lwn.net/Articles/65178/)











Examples of cross platform code : 

1. http://stackoverflow.com/questions/14818084/what-is-the-proper-include-for-the-function-sleep-in-c
#ifdef _WIN32
#include <Windows.h>
#else
#include <unistd.h>
#endif

int main()
{
  pollingDelay = 100
  //do stuff

  //sleep:
  #ifdef _WIN32
  Sleep(pollingDelay);
  #else
  usleep(pollingDelay*1000);  /* sleep for 100 milliSeconds */
  #endif

  //do stuff again
  return 0;
}






What is a typical main function in embedded systems?
Main()
{
ClkInit()
TimerInit()
InterruptsInit()
 
While(1)
{
BackGroundtask()
}
 
}














