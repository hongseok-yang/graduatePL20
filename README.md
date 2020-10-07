# CS520 Theory of Programming Languages, Fall 2020, KAIST 

This is a webpage of the course "CS520 Theory of Programming Languages", which is offered at the KAIST CS department in the fall of 2020. The webpage will contain links to course-related materials and announcements.

CS520 is an advanced graduate-level course on the theories of programming languages. Its goal is to expose students to rigorous mathematical foundations for programming languages and systems, and mathematical techniques for formally reasoning about  programs written in those languages. The course will largely follow Reynolds's textbook "Theories of Programming Languages", which provides good mathematical treatment of a wide range of programming constructs through axiomatic, denotational and operational semantics. 

The prerequisite of the course is CS320, the undergraduate-level programming-language course offered at KAIST, or a similar course. The course will be heavy in math, and we expect students to be comfortable with doing and reading rigorous mathematical proofs. 

## 1. Important Announcements

#### [September 20] Policy for handling late submissions.

We will adopt the following scheme for handling late submissions for homework assignments and critical surveys. The scheme assumes that the total marks are 100.

1. <= One day late (by the midnight of the next day): -10
2. <= Two days late: -20
3. <= Three days late: -30
4. <= Four days late: -40
5. More than four days late: -100.

Of course, we won't accept any late submissions for the final exam.

#### [September 20] [Homework1](https://github.com/hongseok-yang/graduatePL20/blob/master/Homework/Homework1/homework1-questions.pdf) is out.

The homework assignment 1 is out. Submit your solutions in KLMS by 6:00pm on 5 October 2020 (Wednesday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.

## 2. Logistics

#### Evaluation

* Final exam (40%). Homework (30%). Two critical surveys (30%).

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com, office hour: 6:00pm - 7:00pm Monday in ZOOM. You can find more information about it in KLMS.)
* TA: Hyoungjin Lim (email: lmkmkr@kaist.ac.kr)
* TA: Dongwoo Oh (email: dongwoo@kaist.ac.kr)
* Office hours by TAs:  
   * Hyoungjin Lim
      - office hour : 5:00pm - 6:00pm Friday in ZOOM
      - https://us02web.zoom.us/j/4705850446?pwd=VllYUzBXR2VNaDhsNytXVytidzByZz09
      - ID: 470 585 0446
      - PW: 567976  
   * Dongwoo Oh
      - office hour : 4:00pm - 5:00pm Tuesday in ZOOM
      - https://us04web.zoom.us/j/6081604062?pwd=VFhMeXh1SkRUWHE3NFVpZmx4U0Qvdz09
      - ID: 608 160 4062
      - PW: qJ2SY7

#### Place and Time

* Place: ZOOM. If the situation of COVID-19 improves substantially, we will use the room 1101 in the E3 building.
* Time: 9:00am - 10:30am on Monday and Wednesday from 31 August 2020 until 16 December 2020.
* Final exam: 12-hour take-home exam on 12 December 2020 (Saturday). 

#### Online Discussion

* We will use KLMS.

## 3. Homework

Submit your solutions in KLMS. We will create submission folders for all the homework assignments in KLMS.

* [Homework1](https://github.com/hongseok-yang/graduatePL20/blob/master/Homework/Homework1/homework1-questions.pdf) - Deadline: 6:00pm on 5 October 2020 (Monday).

## 4. Tentative Plan

* 08/31 - Introduction and Predicate Logic (Ch1). ([slides](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture1/Lecture1.pdf))
* 09/02 - Predicate Logic (Ch1). ([note1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note6.jpg), [note7](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note7.jpg), [note8](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/note8.jpg), [whiteboard1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep2Board1.png), [whiteboard2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep2Board2.png), [whiteboard3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep2Board3.png))
* 09/07 - Predicate Logic (Ch1). ([whiteboard1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep7Board1.png), [whiteboard2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep7Board2.png), [whiteboard3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep7Board3.png), [whiteboard4](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep7Board4.png))
* 09/09 - Predicate Logic (Ch1). ([whiteboard1(Sep9)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep9Board1.png), [whiteboard2(Sep9)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep9Board2.png), [whiteboard3(Sep9)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep9Board3.png), [whiteboard4(Sep9)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep9Board4.png), [whiteboard1(Sep14)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep14Board1.png), [whiteboard2(Sep14)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture2/Sep14Board2.png))
* 09/14 - The Simple Imperative Language (Ch2). ([note1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/note6.jpg), [whiteboard1(Sep14/16)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep14:16Board1.png), [whiteboard2(Sep14/16)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep14:16Board2.png), [whiteboard3(Sep14/16)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep14:16Board3.png), [whiteboard4(Sep14/16)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep14:16Board4.png))
* 09/16 - The Simple Imperative Language (Ch2). 
* 09/21 - The Simple Imperative Language (Ch2). ([whiteboard1(Sep21)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep21Board1.png), [whiteboard2(Sep21)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep21Board2.png), [whiteboard3(Sep21)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep21Board3.png), [whiteboard4(Sep21)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep21Board4.png))
* 09/23 - The Simple Imperative Language (Ch2). ([whiteboard1(Sep23)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep23Board1.png), [whiteboard2(Sep23)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep23Board2.png), [whiteboard3(Sep23)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep23Board3.png), [whiteboard4(Sep23)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture3/Sep23Board4.png))
* 09/28 - Program Specification and Their Proofs (Ch3). ([note1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/note4.jpg), [whiteboard1(Sep28)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/Sep28Board1.png), [whiteboard2(Sep28)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/Sep28Board2.png), [whiteboard3(Oct5)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/Oct5Board1.png), [whiteboard4(Oct5)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/Oct5Board2.png), [whiteboard5(Oct5)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture4/Oct5Board3.png))
* __**09/30 - NO LECTURE. Thanksgiving Day.**__
* 10/05 - Failure, Input-Output, and Continuation (Ch5). ([note1](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note6.jpg), [note7](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/note7.jpg), [whiteboard1(Oct5)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/Oct5Board1.png))
* 10/07 - Failure, Input-Output, and Continuation (Ch5). ([whiteboard1(Oct7)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/Oct7Board1.png), [whiteboard2(Oct7)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/Oct7Board2.png), [whiteboard3(Oct7)](https://github.com/hongseok-yang/graduatePL20/blob/master/Lectures/Lecture5/Oct7Board3.png))
* 10/12 - Transition Semantics (Ch6). 
* 10/14 - Transition Semantics (Ch6). 
* __**10/19, 10/21 - NO LECTURES. Midterm Exam.**__
* 10/26 - An Introduction to Category Theory (Tennent Ch8). 
* 10/28 - An Introduction to Category Theory (Tennent Ch8). 
* 11/02 - Recursively-Defined Domains (Tennent Ch10). 
* 11/04 - Recursively-Defined Domains (Tennent Ch10).
* 11/09 - The Lambda Calculus (Ch10). 
* 11/11 - The Lambda Calculus (Ch10). 
* 11/16 - An Eager Functional Language (Ch11). 
* 11/18 - An Eager Functional Language (Ch11).
* 11/23 - Continuation in a Functional Language (Ch12). 
* 11/25 - Continuation in a Functional Language (Ch12). 
* 11/30 - A Normal-Order Language (Ch14).
* 12/02 - The Simple Type System (Ch15).
* __**12/07, 12/09 - Possibly NO LECTURES. KAIST Undergraduate Admission.**__
* __**12/14, 12/16 - NO LECTURES. Final Exam.**__


## 5. Studying Materials

We will mainly follow Reynolds's book, but study the materials appearing in Chapters 8 and 10 of Tennent's book.

* Main Textbook 1 : [Theories of Programming Languages, John C Reynolds](https://www.cambridge.org/core/books/theories-of-programming-languages/19530A88F3471B2A7D9891770B21DAF9), Cambridge University Press, 1998. 
* Main Textbook 2 : Semantics of Programming Languages, Robert D. Tennent, Prentice Hall, 1991. Chapters 8 and 10 only.

In addition to the two books above, the following books will have further information about the topics covered in the course. In particular, Gunter's book goes deep into the domain theory, and Pierce's book into the type theory.

* Auxiliary Textbook 1 : Semantics of Programming Languages: Structures and Techniques, Carl A. Gunter, MIT Press, 1992.
* Auxiliary Textbook 2 : Types and Programming Languages, Benjamin C. Pierce, MIT Press, 2002.
* Auxiliary Textbook 3 : Formal Semantics of Programming Languages: an Introduction, Glynn Winskel, MIT Press, 1993.

The following classic papers or their recent reprints contain deep insight into some of topics that we study throughout the course.

* John C. Reynolds, [Definitional Interpreters for Higher-Order Programming Languages](https://doi.org/10.1023/A:1010027404223), Higher-Order and Symbolic Computation, 1998. 
* Luis Damas and Robin Milner, [Principal Type-Schemes for Functional Programs](https://dl.acm.org/citation.cfm?id=582176), POPL 1982.

## 5. Two Critical Surveys

One important part of this course is to study assigned topics for yourself, and write surveys about them, which also contain critiques or original thoughts of the student. It accounts for the 30% of the total marks of this course. In order to get full marks, a student has to show in his or her write-up that she or he has understood the topics well, carried out in-depth studies on the topics, and thought hard and originally about them. Our evaluation adopts the following criterion: the clarity of writing (20%), the level of understanding a topic and existing work about it (40%), and the demonstration of original thoughts and insights (40%). Here are the details of this assignments.

1. Don't postpone this assignments until the last moment.
2. There are two assignments. In both cases, a submission should be at most 3 pages not including bibliography.
3. First assignment:
   1. Topic: Concurrent separation logic.
   2. Deadline: __**23:59 of the 30th of October in 2020 (Friday). Summit in KLMS.**__
   3. Some references that may help you to start: 
      1. Peter O'Hearn. [Resources, Concurrency, and Local Reasoning.](http://www0.cs.ucl.ac.uk/staff/p.ohearn/papers/concurrency.pdf) This is the paper that started concurrent separation logic.
      2. Stephen Brookes and Peter O'Hearn. [Concurrent Separation Logic.](https://dl.acm.org/doi/pdf/10.1145/2984450.2984457)
      3. Peter O'Hearn. [Separation Logic.](https://cacm.acm.org/magazines/2019/2/234356-separation-logic/pdf)
      4. Peter O'Hearn, John Reynolds, and Hongseok Yang. [Local Reasoning about Programs that Alter Data Structures.](http://www0.cs.ucl.ac.uk/staff/p.ohearn/papers/localreasoning.pdf) This paper describes one of the key ideas behind separation logic, called local reasoning.
      5. Stephen Brookes. [A Semantics for Concurrent Separation Logic.](https://www.cs.cmu.edu/~brookes/papers/seplogicrevisedfinal.pdf)
   4. Questions to think about:
      1. What is separation logic? What is concurrent separation logic?
      2. Which aspects of concurrent separation logic help construct the proofs of concurrent programs more easily?
      3. What recent research results result from concurrent separation logic?
      4. Can you find a new application where concurrent separation logic or its key ideas can be applied?
      5. How would you improve concurrent separation logic?
      6. If you want to show the termination (more generally liveness properties), how should you extend concurrent separation logic?
4. Second assignment.
   1. Topic: Relational parametricity.
   2. Deadline: __**23:59 of the 7th of December in 2020 (Monday). Summit in KLMS.**__
   3. Some references that may help you to start:
      1. John Reynolds. [Types, Abstraction and Parametric Polymorphism.](http://www.cs.cmu.edu/afs/cs/user/jcr/ftp/typesabpara.pdf).
      2. Philip Wadler. [Theorems for free!](https://dl.acm.org/doi/pdf/10.1145/99370.99404).
      3. Chapter 17 of the textbook by Reynolds.  
      4. John Reynolds. [An Introduction to Polymorphic Lambda Calculus.](http://citeseerx.ist.psu.edu/viewdoc/download;jsessionid=F12E218CB6AA7DA6A31C9DDDB12DEE2E?doi=10.1.1.7.9916&rep=rep1&type=pdf)
      5. The above papers are classic papers on this topic. I suggest you to have a look at more recent papers on this topic as well, published in PL conferences and journals such as POPL, LICS, MFPS, TOPLAS.
   4. Questions to think about:
      1. What is polymorphism? 
      2. How parametric polymorphism and ad-hoc polymorphism differ and get realised in programming languages? 
      3. How relational parametricity formalises parametric polymorphism?
      4. What are the consequences of relational parametricity for properties of programs? 
      5. How does relational parametricity relate to other programming language concepts such as data abstraction?
      6. Can you find a new way of using the key idea behind relational parametricity?
      7. What do researchers work on relational parametricity nowadays?
