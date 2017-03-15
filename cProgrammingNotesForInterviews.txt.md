1. Typing in languages :
   1. https://pythonconquerstheuniverse.wordpress.com/2009/10/03/static-vs-dynamic-typing-of-programming-languages/
   2. http://www.chiark.greenend.org.uk/~sgtatham/cdescent/
   3. http://www.cs.cornell.edu/courses/cs1130/2012sp/1130selfpaced/module1/module1part4/strongtyping.html



2. Value Semantics and Reference Semantics :
   1. https://akrzemi1.wordpress.com/2012/02/03/value-semantics/
   2. http://www.chiark.greenend.org.uk/~sgtatham/cdescent/
   3. http://wiki.c2.com/?PointersAndReferencesAreTheSameThing

3. Understanding cases of undefined behaviour :
   1. https://www.nayuki.io/page/undefined-behavior-in-c-and-cplusplus-programs


4. Reading * and & in different ways
   1. https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-088-introduction-to-c-memory-management-and-c-object-oriented-programming-january-iap-2010/lecture-notes/MIT6_088IAP10_lec02.pdf
   2. * : Take the value of ,& : Take the address of 


5. understanding stack frames during function calls : 
   1. https://www.cs.cmu.edu/~fp/courses/15213-s07/misc/asm64-handout.pdf
   2. http://www.ugrad.cs.ubc.ca/~cs411/2009W2/downloads/x86.pdf
   3. https://cseweb.ucsd.edu/classes/sp14/cse141-a/Slides/01_ISA-Part%20II-annotated.pdf
   4. pg 34 of book - Pointers in C
   5. http://web.archive.org/web/20140719092417/http://www.altdev.co/2011/12/14/c-c-low-level-curriculum-part-3-the-stack/


6. ISA (the interface between software and hardware) :
   1. https://stefanheule.com/blog/how-many-x86-64-instructions-are-there-anyway/
   2. https://0xax.github.io/asm_1/
   3. http://flint.cs.yale.edu/cs421/papers/x86-asm/asm.html


7. Reading C declarations :
   1. http://users.ece.utexas.edu/~ryerraballi/CPrimer/CDeclPrimer.html
   2. http://unixwiz.net/techtips/reading-cdecl.html
   3. https://untroubled.org/articles/cdecls.txt
   4. http://ieng9.ucsd.edu/~cs30x/rt_lt.rule.html
   5. http://codinghighway.com/2013/12/29/the-absolute-definitive-guide-to-decipher-c-declarations/
   6. http://www.programmerinterview.com/index.php/c-cplusplus/c-declarations/
   7. https://www.codeproject.com/Articles/7042/How-to-interpret-complex-C-C-declarations
   8. Also, found some more resources explaining the right to left rule
      of reading C declarations :
      http://stackoverflow.com/questions/13247473/figuring-out-c-declarations
      (somebody suggested using spiral rule in above URL but
      then someone advised against spiral rule in link below -
      https://news.ycombinator.com/item?id=12775735


8. Differentiating between declaration and definition : 


9. Scoping rules in C
   1. https://www.cs.uic.edu/~jbell/CourseNotes/C_Programming/Functions.html

10. Const pointers


11. programming language comparison
    1. https://pythonconquerstheuniverse.wordpress.com/2009/10/03/python-java-a-side-by-side-comparison/

12. Problems with pointers
    - memory leak
    - stale pointer
    - type safing violation with pointers
    - integer overflow



13. programming tips
    1. https://www.cs.uky.edu/~raphael/programming.html



14. bitwise operations

15. things going wrong in a C program
- accessing stale pointers
- allocating wrong size of memory
- overrunning the bounds of an array
- freeing th same pointer twice
- integer overflow problem

Listing out problems - https://embeddeddreams.quora.com/Embedded-Basics-What-are-the-reasons-for-software-hangs-especially-in-embedded-systems-How-to-write-good-softwar
Dealing with problems - http://pfacka.binaryparadise.com/articles/guide-to-advanced-programming-in-C.html



16. Experiments with stack size of OSes
merge sort program fails due to max recursion depth reached
(how to understand growing stack) : https://wr.informatik.uni-hamburg.de/_media/teaching/sommersemester_2014/cgk-14-rieck-zeig-e-und-dynamische-_speicherverwaltun-report.pdf
https://github.com/theli-ua/derp/blob/master/Introduction%20to%20Algorithms/mergesort.py


17. C projects to be done in free time : 
https://24alpha.wordpress.com/2007/12/18/how-to-get-gcc-to-interleave-assembly-output-with-original-source-code/

18. understanding the concept of wrappers for system calls :
http://oss.sgi.com/LDP/LDP/LG/current/ramankutty.html

19. optimizations : 
http://www.azillionmonkeys.com/qed/optimize.html
http://www.agner.org/optimize/optimizing_assembly.pdf

20. understanding preprocessing : 
https://calleerlandsson.com/the-four-stages-of-compiling-a-c-program/#preprocessing

21. understanding the memory model :
http://www.tenouk.com/ModuleW.html


22. understanding disassembly : 
http://www.expobrain.net/2013/06/16/disassembly-c-code-for-fun-part-1/
http://patshaughnessy.net/2017/1/20/pointers-in-c-and-x86-assembly-language
http://stackoverflow.com/questions/22821973/how-do-stack-and-registers-work-in-assembler?rq=1
http://stackoverflow.com/questions/27629390/what-is-the-actual-relation-between-assembly-machine-code-bytecode-and-opcode?rq=1
http://stackoverflow.com/questions/1289881/using-gcc-to-produce-readable-assembly?rq=1



23. understanding pointer manipulations through assembly/disassembly :
http://patshaughnessy.net/2017/1/20/pointers-in-c-and-x86-assembly-language

24. alignment, padding, byte packing and unpacking :
   1. https://embeddeddreams.quora.com/Concept-What-is-Data-alignment
   2. https://embeddeddreams.quora.com/Concept-What-is-Structure-padding
   3. https://embeddeddreams.quora.com/Examples-What-is-structure-padding-part-2
   4. http://c-faq.com/struct/align.esr.html
   5. best explanation for requirement of alignment with diagram : http://stackoverflow.com/questions/381244/purpose-of-memory-alignment?rq=1
   6. http://www.catb.org/esr/structure-packing/
   7. http://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/





25. bottom up compilation : 
http://www.bottomupcs.com/compilation_example.xhtml
http://stackoverflow.com/questions/11473973/understanding-assembly-language-output-of-a-c-program?rq=1


26. Bit Fields
http://hackaday.com/2015/08/28/firmware-factory-bit-fields-vs-shift-and-mask/
http://www.pagetable.com/?p=250
http://www.thegeekstuff.com/2013/08/c-struct-union-bit-field/?utm_source=feedburner

ana amaal kamuhanndis hasuf



pages from books

Concepts I know
-pass by value and pass by reference mechanisms in functions

Concepts I learnt recently
1. Structure can contain pointer variables as its members
2. Seg fault happens when a pointer does not point to a valid memory address
3. const pointer can point to only one address


personal questions
pointers in C
ch 2:
what does it mean when we say address of and dereference operator are unary in nature ?


Important pages of books to revise :

1. Seg fault due to incorrect use of free : page 33
2. Pointers and constants : pg 36-38
2. Pointers and constants : pg 36-38
3. understanding cryptic pointer expression :  page 40-42
4. Why pointer arithmentic is different as explained by assembly code? : pg48
5. Array of pointers : pg54



Programming Resources

C
Possible Interview questions :
Pointers :
Small Tasks :








