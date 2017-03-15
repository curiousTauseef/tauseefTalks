1. Typing in languages
https://pythonconquerstheuniverse.wordpress.com/2009/10/03/static-vs-dynamic-typing-of-programming-languages/
http://www.chiark.greenend.org.uk/~sgtatham/cdescent/
http://www.cs.cornell.edu/courses/cs1130/2012sp/1130selfpaced/module1/module1part4/strongtyping.html



2. Value Semantics and Reference Semantics
https://akrzemi1.wordpress.com/2012/02/03/value-semantics/
http://www.chiark.greenend.org.uk/~sgtatham/cdescent/
http://wiki.c2.com/?PointersAndReferencesAreTheSameThing

3. Understanding cases of undefined behaviour : 
https://www.nayuki.io/page/undefined-behavior-in-c-and-cplusplus-programs


4. Reading * and & in different ways
https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-088-introduction-to-c-memory-management-and-c-object-oriented-programming-january-iap-2010/lecture-notes/MIT6_088IAP10_lec02.pdf
* : Take the value of 
& : Take the address of 


5. understanding stack frames during function calls : 
https://www.cs.cmu.edu/~fp/courses/15213-s07/misc/asm64-handout.pdf
http://www.ugrad.cs.ubc.ca/~cs411/2009W2/downloads/x86.pdf
https://cseweb.ucsd.edu/classes/sp14/cse141-a/Slides/01_ISA-Part%20II-annotated.pdf
pg 34 of book - Pointers in C
http://web.archive.org/web/20140719092417/http://www.altdev.co/2011/12/14/c-c-low-level-curriculum-part-3-the-stack/


6. ISA (the interface between software and hardware) :
https://stefanheule.com/blog/how-many-x86-64-instructions-are-there-anyway/
https://0xax.github.io/asm_1/
http://flint.cs.yale.edu/cs421/papers/x86-asm/asm.html


7. Reading C declarations :

8. Differentiating between declaration and definition : 


9. Scoping rules in C
https://www.cs.uic.edu/~jbell/CourseNotes/C_Programming/Functions.html

10. Const pointers


11. programming language comparison
https://pythonconquerstheuniverse.wordpress.com/2009/10/03/python-java-a-side-by-side-comparison/

12. Problems with pointers
- memory leak
- stale pointer
- type safing violation with pointers
- integer overflow
- 


13. programming tips
https://www.cs.uky.edu/~raphael/programming.html



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



23 understanding pointer manipulations through assembly/disassembly :
http://patshaughnessy.net/2017/1/20/pointers-in-c-and-x86-assembly-language

24. alignment, padding, byte packing and unpacking :
https://embeddeddreams.quora.com/Concept-What-is-Data-alignment
https://embeddeddreams.quora.com/Concept-What-is-Structure-padding
https://embeddeddreams.quora.com/Examples-What-is-structure-padding-part-2
http://c-faq.com/struct/align.esr.html
best explanation for requirement of alignment with diagram : http://stackoverflow.com/questions/381244/purpose-of-memory-alignment?rq=1
http://www.catb.org/esr/structure-packing/
http://www.geeksforgeeks.org/structure-member-alignment-padding-and-data-packing/





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







AWS jobs
-------
Job Title
Software Development Engineer

Job Description

Your challenge

Philips is a global health technology company where many of the best and brightest developers can openly collaborate to build a more connected and healthier society.

Are you passionate about the intersection of cloud computing, big data, analytics, the Internet-of-Things (IoT) and the advancement of medicine? Do you have the ability to push the boundaries of innovating unique cutting-edge solutions that bring together medicine and technology? Do you have a unique combination of deep technical knowledge, out-of-the-box thinking and strong interpersonal skills?

Responsibilities

Working for a worldwide leader in health technology brings much personal fulfillment, as well as unique challenges. As part of our company, you will be responsible for…

    Making a huge Global impact, working side-by-side a highly motivated and skilled software development team focused on the creation of next generation medical information platforms, using cutting edge technologies for cloud, web and mobile applications and data analytics.

Key areas of responsibilities (KARS) for this role include:

    Develop applications and components within a highly motivated software development team focused on the creation of next generation medical information systems -and applications.

    Learn and contribute to solving problems with our highly experienced architects and software development team.
    Work in an environment that embodies and embraces new ideas and innovations through agile methodologies and innovation marathons.
    Push the innovation and technology boundaries to bring breakthrough solutions to complex clinical and business problems.
    Utilize software design patterns to enhance software quality by addressing fundamental challenges in large-scale system development. These challenges include communication of architectural knowledge among developers, accommodating new design paradigms or architectural styles and avoiding development traps and pitfalls that are usually learned only by experience.

Your team

Work on our top-notch software development team in a fast-paced, high energy, and fun work environment.  If you are interested joining a world-class team in the development of advanced technology software medical products that help to save and improve patients’ lives every day, this could be the role for you.

Location:

Andover, MA

We are looking for:

Developers that offer more than just code. Our skilled teams work by an innate code of caring about and making life better for others through their innovation and collaboration. The solutions you will develop are bigger than the next big tech gadget. Your work exponentially elevates the level of care for everyone, from healthcare patients to kids learning how to brush their teeth. A career with Philips will allow you to use your skills to help transform the future of healthcare while positively impacting lives around the world.

Specific skill requirements for this role include:

    Strong understanding of object oriented software development concepts and methodologies.

    Solid understanding of Design and implementation of scalable, secure cloud architecture based on Amazon Web Services, leveraging AWS Data pipeline to process and move data using AWS services like EC2, S3, Hive, Elastic MapReduce, DyanamoDB and PostgreSQL.

    Must be proficient in the following technologies Java, Spark, Spring Boot, RabbitMQ, MQTT, SQL, Java, Angular JS, HTML5.

    Understanding of design patterns and practical experience in applying those patterns to address fundamental challenges in large scale, mission critical system development and influencing software engineering best practices within your team.

    Strong problem solving skills and the ability to produce high quality work independently and work well in a team.
    Ability to work effectively in ambiguous situations using critical thinking skills and be decisive while working cooperatively with others.

This role comes with competitive compensation, benefits and a generous holiday/vacation offering, but that’s not all. At Philips we offer you:

The chance to develop innovations that matter to people from the hospital to the home. This includes collaborating with skilled developers on solutions used by doctors and patients all over the world

A Collaborative Culture. Some of our teams are moving to the Agile methodology of software development where developers are expected to voice opinions, research and propose different technologies to solve complex problems. You will work in close-knit teams dependent upon each other for success.

Work and live healthy, don’t live to work. There is no limit to paid time off due to illness, issues with immediate family, doctor’s appointments, or personal matters that cannot be handled while you’re work. Also, our Workplace Innovation program allows non-traditional start and end times, as well as the ability to work from home or another Philips office with agreement from your manager.

Philips is an equal opportunity employer. All qualified applicants will receive consideration for employment without regard to race, color, religion, age, sex (including pregnancy), sexual orientation, gender identity, national origin, genetic information, creed, citizenship, disability, protected veteran or marital status. 

As an equal opportunity employer, Philips is committed to a diverse workforce. In order to ensure reasonable accommodation for individuals protected by Section 503 of the Rehabilitation Act of 1973, the Vietnam Veterans' Readjustment Act of 1974, and Title I of the Americans with Disabilities Act of 1990, applicants that require accommodation in the job application process may contact 888-367-7223, option 5, for assistance.

#LI-AJ1

Contact

In case of technical difficulties with your job application, such as login issues or a need to reset your password, please send an email to careersite@philips.com. 
(Note: To ensure fairness and legal compliance in our recruitment processes, only technical issues will be monitored through the above inbox. Please do not submit resumes or applications to this email, as they will not be reviewed. Only applications received through the online application process will be considered.)



-----------------------
Job Title
Scientist (m/f) Data Analytics/Big Data

Job Description

Philips Research is a global organization that helps Philips introduce meaningful innovations that improve people’s lives. We provide technology options for innovations in the area of health and well-being, targeted at both developed and emerging markets. Positioned at the front-end of the innovation process, we work on everything from spotting trends and ideation to proof of concept and – where needed – first-of-a-kind product development.

You will be part of a growing team of colleagues focusing on data analytics services within the Hamburg Research laboratory. 

Your Responsibilities

As a data scientist in Philips Research you will enable Philips and its customers to make the most out of their data. You will analyze diverse data sources with a broad range of tools and methods. In close collaboration with our business partners, you will co-create internal and customer-facing analytics solutions and evaluate them in the real world.

    Drive the full data analytics stack: data exploration, preparation, ETL, modeling, visualization
    Work with our business partners to transform their real-life challenges to analytics solutions
    Help develop front-end tools to show and evaluate your methods
    Contribute to the field of data science, present your work at conferences and in journals

Your Profile

Your work in our team has a direct impact on how we and our customers operate. We practice an agile way of working that gives you great flexibility in how you approach your tasks. Applying your unique skills and realizing your own ideas is at the core of your work.

We are looking for people who want to deliver excellent results for our customers in a team with other highly qualified, innovative colleagues.

    University degree and PhD in Informatics or similar
    Proven capabilities in data handling, processing and visualization
    Solution-driven mind set, willingness to engage in the subject matter of the task
    Ability to independently develop innovative analytics algorithms
    Very good knowledge of open source analytics and visualization tools (e.g. Python, d3)
    Expertise in data modeling, databases, SQL and Web programming
    Excellent communication and teamworking skills
    Ability to efficiently work in teams
    Passion for innovation
    Proficiency in English language, German would be a plus

Philips encourages people with disability to apply.

Please upload your complete documents, incl.  CV, diplomas, PhD and a list of your publications.

Please apply only online and include in your cover letter your salary expectations and the earliest possible starting date/your period of notice.

As a company for health and wellbeing the compatibility of our employees’ professional and private life is an important aspect for Philips. Therefore we offer numerous services to support you for example "Kids and more" as part of our family services, the “Philips in Balance - health program”, as well as modern working time models.

=================================
Job Title
Development Engineer 3D Pathology & Molecular Data Fusion

Job Description

Your challenge

Designed around the needs of pathologists, Philips offers an integrated Digital Pathology Solution, improving the quality and effectiveness of the operation in hospitals and research centers that have deployed digital pathology. Image analytics will play an increasingly important role in improving the quality and effectiveness of digital pathology. Image analysis algorithms range from computer aided measurements and characterization to algorithms assisting the diagnosis.

As a Development Engineer 3D Pathology & Molecular Data Fusion, you will strengthen the Advanced Development team with brain- and man- power to ensure the timely release of high quality products, systems and services to ensure the continued growth in an agile environment. Clinical opinion leaders have indicated that the next game changer is the step towards multi-modal 3D pathology.

Your responsibilities

Within this role you will be able to:

    Create and demonstrate a meaningful reconstruction and data fusion of 3D pathology images with other advanced imaging techniques such as e.g. optical coherence tomography and mass spectroscopy imaging.

We expect you to deliver:

    Proof of concept for 3D reconstruction of bright field microscopy image data for efficiency and/or quality enhancement for pathologists
    Proof of concept for data fusion of multiple 3D imaging modalities as a key tool for precision diagnostics and prognostics
    Demonstration of proof of concept in a clinical pathology lab

Your team

The Philips Digital Pathology Solutions (PDPS) venture started in 2007 and is based in US, Europe and Asia and keeps expanding. Our mission: In a world with increasing challenges for cancer diagnostic procedures and quality of patient care we want to be number one in empowering Pathologists with Digital Pathology Solutions via the best Pathology scanners, Image Management System, workflow and Image Analysis solutions available. This helps the pathology laboratory and the pathologists to work more effectively, leading to higher quality diagnosis and as a result better patient care.

When you walk into work you will be joining a truly entrepreneurial team of over 330 employees spread across 8 countries, all passionate about defining the future, growing the business and having fun. You will be considered an “early joiner” to the Philips Emerging Businesses family.

This position will be located at our facility in Best, The Netherlands.

Our offer 

We believe that every mega growth period creates an exceptional career runway. In fact, the Emerging Businesses leadership team gets out of bed every morning with the sole focus of growing the business and growing the people who contribute to it. Luckily, you are the benefactor of this unique opportunity and leadership commitment- likely to experience an exciting high stakes, mobility-focused environment from which to create your own future – personally, professionally & financially.

We welcome you to a challenging, innovative environment with great opportunities for you to explore.

You will learn to:

    Create meaningful solutions for healthcare based on data fusion of 3D pathology and molecular imaging
    Team up with a multi-disciplinary development team
    Collaborate with molecular biologists, bio-informatics engineers and pathologists in partner academic hospitals to explore, create and validate new innovative concepts in the area of data fusion and big data analytics

We offer you 3 x 9 months projects in 2 countries and 2 businesses in which we would like you to start the first one per September 2017. This project will be your start of your 27 months journey through the Philips Emerging Business organization.

We are looking for

Our ideal candidate has an analytic and problem solving mindset, and has/is:

    Master degree in:
        (applied) mathematics
        biomedical engineering
        molecular biology
        computer science
        experimental physics
        (bio) informatics
    Flexible and open attitude, good (customer) communication skills in English;
    Self-starting capabilities and an entrepreneurial mindset;
    Preferably affinity with working in cross functional teams;
    Relevant experience with:
        Computer vision, image analysis & processing, machine learning (e.g. deep learning and random forest, convolutional neural networks)
        Object detection, feature extraction, segmentation and image recognition
        Statistical modeling& analysis
        Analyzing big data sets, efficient computation and code optimization
        R, Theano, Caffe, TensorFlow, Torch, MATLAB, OpenCV, Python, Scala, C / C++ (or similar)

If you recognize yourself in this profile and would like to take this challenge, we invite you to apply before 4-5-2017!

Recruitment process 

If you’re interested in this opportunity to join us, please upload your resume and motivation letter.

    if you pass the pre-selection round you will be asked to make an online ability test;
    if you achieve the required score on this test, you will be invited for a Skype interview with our Campus Recruiter;
    if you pass this interview, you will be invited for a follow-up interview with the business
    if you pass the business Skype interview you will be invited for a face-to-face business interview proceeded by a floor tour (half a day in your agenda)
    When you successfully complete the selection process you are able to start per 1st of September 2017 in your first assignment which are especially created for this program.

Contact

In case of technical difficulties with your job application, such as login issues or a need to reset your password, please send an email to careersite@philips.com. 
(Note: To ensure fairness and legal compliance in our recruitment processes, only technical issues will be monitored through the above inbox. Please do not submit resumes or applications to this email, as they will not be reviewed. Only applications received through the online application process will be considered.) 


-----------------------
