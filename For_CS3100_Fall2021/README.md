* Holidays that affect our classes
  - Labor Day: 9/6/21
  - Fall Break: 10/10/21 - 10/17/21
  
* -------------------------------------------------------

* Week-1 **Reading**: Chapters 1, 2, 3. __Outcomes:__
  Emerge with complete understanding of the basics of
  computability, why studying formal language matters, and know how to construct
  languages using set operations, concatenation, and exponentiation. They also
  begin studying Kleene-star. As for practical matters, they understand the course
  objectives, how to run the course software and submit the required material for
  grades.

   - 1:8/23
     - Run the Notebooks within 01_Computability_Languages/ 
     - Quiz-1 given; due 8/27 11:59pm, covers L1,2
     - Asg-1 given, due 9/3/21 11:59pm, covers L1,2
   - 2:8/25
     - Run the Notebooks within 01_Computability_Languages/
   
* Week-2 **Reading**: Chapters 3, 4 (except 4.6 thru 4.8), 5, 6. __Outcomes:__
  Finish understanding Kleene-star, and are able to design
  DFA using two methods: By knowing how to encode salient information in DFA states
  (by naming DFA states to retain this info) and by Boolean operations on DFA (union,
  intersection, complement). They know how to document DFA using literate-programming
  methods of annotating comments within a simple DFA markdown. They are able to
  automatically build, and test DFA, following important principles of software testing.

   - 3:8/30
     - Run the Notebooks within 02_Basic_DFA/
     - Quiz-2 given; due 9/3 11:59pm, covers L3,4
     - Asg-2 given, due 9/10/20 11:59pm, covers L3,4
   - 4:9/1
     - Run the Notebooks within 03_Advanced_DFA/ 
   
* Week-3 **Reading** Chapter 6 (skip 6.4 and 6.5), 7.  __Outcomes:__
Outcomes: Understand the importance of nondeterminism in computer
  science, and what nondeterministic finite-state automata are. They understand how to
  convert NFA to DFA via subset construction. They are able to witness, through actual
  hands-on activity, that NFA can blow up exponentially when converted to DFA. They
  may also obtain a DFA directly, and check against results from NFA2DFA using a
  DFA graph isomorphism check, thus showing the power of the Myhill-Nerode theorem to
  help check one software construction method against the other, to catch bugs.
   
   - *:9/6 (Labor day holiday)
     - Run the Notebooks within 04_NFA/
     - Quiz-3 given; due 9/17 11:59pm, covers L5,6
     - Asg-3 given, due 9/17/21 11:59pm, covers L5,6
     
   - 5:9/8
     - Run the Notebooks within 05_NFA2DFA/
   
* Week-4 **Reading** Chapter 8, 9.  __Outcomes:__
  Understand what regular expressions are, and how they
  can be converted into NFA, and back to RE. They understand all the algorithmic
  details, solving interesting real-world problems using regular expressions, including
  error-correcting finite-state machines, and the encoding of the Postage Stamp Problem
  (also known as the Coin Problem).

   - 6:9/13
     - Run the Notebooks within 06_RE/
     - Asg-4 given, due 9/24 11:59pm, covers L7,8    
   - 7:9/15
     - Run the Notebooks within 07_NFA2RE/
   
* Week-5 **Reading** Chapter 6.4.  __Outcomes:__
  Take a midterm to assess the previous objectives. Ungraded practice
  problems would have been given out each week; discuss those in class. The exam is
  a take-home timed exam on Canvas. After the exam, learn two algorithms for DFA
  minimization, one based on dynamic programming, and the other based on Brzozowski's
  minimization which can be realized using one line of code as ("reverse; determinize;
  reverse; determinize").

   - 8:9/20
     - Quiz-4 given; due 9/24 11:59pm, reviews material to date
     - Review of Asg 1-3
     - Run the Notebooks within 08_Min_DFA/
     
   - 9:9/22
     - EXAM SIMULATION in breakout groups

* Week-6

   - 10:9/27 **MT-1**
     - **BOOK SECTIONS**
       - CHAPTERS 1-7 (Except Pumping Lemma and Details of  Dynamic-programming Based Minimization)
	 
     - **NOTEBOOK PART**
       - COVERS Asg 1-3 (75% of the overall score)
       
     - **QUIZ PART**
       - Covers Quiz 1-3 ; Best of two 40-min attempts ;  No "incorrect answer" feedback ; 25% of the overall score
     - **Given out / DUE **
       - 9/27/21 9 AM or before / DUE 9/28/21 11:59pm

* **Reading** Chapter 4.6 through 4.8.  __Outcomes:__
  Understand the limitations of finite automata by
  studying the regular language Pumping Lemma. Also begin introducing
  Pushdown Automata.
  
   - 11:9/29
     - Run the Notebooks within 09_Reg_PL/
     - Quiz-5 given; due 10/6 11:59pm, covers L11,12
     - Asg-5 given; due 10/8 11:59pm, covers L11,12
     - In-class: Problem-solving about PL

* Week-7  **Reading** Chapters 11 (except 11.9), 12.  __Outcomes:__
  More details of pushdown automata followed by an introduction to
  context-free grammars and languages.  Ambiguity.
  Consistency and Completeness.

   - 12:10/4
     - Run the Notebooks within 10_PDA/
     - In-class: Problem-solving about PDA
   
   - 13:10/6
     - Quiz-6 given; due 10/11 11:59pm, covers L13,14
     - Asg-6 given; due 10/18/21 11:59pm, covers L13,14
     - Run the Notebooks within 11_CFG/
     - Run the Notebooks within 12_CFG2PDA/
     
* Week-8 **Reading** Chapters 11 (except 11.9), 12.  __Outcomes:__
 Designing a calculator.
 Understand how NFA can be translated into Linear CFGs.
 The notions of Consistency and Completeness. Demonstration on simple grammars.
 Chapters 10 (derivatives).

   - 14:10/18
     - Conversion of CFG to PDA
     - Quiz-7 given; due 10/22 11:59pm, covers L15,16
     - Asg-7 given; due 10/29/21 11:59pm, covers L15,16 (calculator design, derivatives)
     - LOOK FOR ASSIGNMENT-7 as a PDF file that will cover
       - 13_Linearity_Amb/
       - 14_Calculator/
       - 15_Derivatives/
     - Run the Notebooks provided within 13_Linearity_Amb/
     - Run the Notebooks provided within 14_Calculator/
     - The directory ASSIGNMENT-7/ is created under 13_Linearity_Amb/     
   
   - 15:10/20
     - The basics of derivative-based Pattern Matching.
     - Run the Notebooks  provided within 15_Derivatives/     
     
* Week-9 **Reading** Now read 11.9 (a pumping lemma for
  context-free languages).  __Outcomes:__
  Applying the CFL PL for proving that a given language is
  not context-free.
  
   - 16:10/25
     - Quiz-8 given; due 10/29 11:59pm, covers L117,18
     - Run the Notebooks within 17_DTMs_and_NDTMs/
     - This is required for ASSIGNMENT-8.     
     - ASSIGNMENT-8 is contained in   16_CFL_PL/. A notebook is given
       for you to submit your answers (named as usual).
     - Asg-8 given; due 11/05/20 11:59pm, covers 
       the CFL Pumping Lemma and its applications. It also
       has a few ready-made TMs for you to run.
     - A notebook rendering of the CFL PL attempted: 16_CFL_PL/		
     
   - 18:10/27


* Week-10 **Reading** Chapter 13.  __Outcomes:__
  Learn the basics of
  designing Turing machines.
  
   - 19:11/01
     - Quiz-9 given; due 11/05 11:59pm, covers Turing Machines
     - How to design DTMs and NDTMs 
     - Run the Notebooks within 18_More_TM_Exs/
     
   - 20:11/03
     - Review of MT-2
     - **MIDTERM EXAM-2** covering Asg 4-7 PLUS Quizzes 5-8
     - Specific portions:
       - Regular Expressions in Asg-4 (some of the MT-1 practice that was not asked)
       - NFA to RE
       - Min-DFA (dynamic-programming based)
       - **Regular Language Pumping Lemma**
       - PDA (Chapter 12)
       - CFG (Chapter 11), **Excluding the CFL PL**
     - Given out 11/06 Saturday by 9am
     - Due 11/08 Monday by 11:59pm     
   
* Week-11 **Reading** Chapters 13, 14 (begin reading) __Outcomes:__
  NDTMs and the Chomsky Hierarchy. Halting problem,
  and the basics of undecidability proofs.
  
   - 21:11/8
     - **ASG-9 given**, Due 11/19/21 11:59pm, covers the
       CFL PL, DTM, and NDTM

     - ASG-9 is within 18_More_TM_Exs/
       
   - 22:11/10
     - Chapter 14, Basic Undecidability Proofs.
       Chapter 15, The Post Correspondence Problem.
     - Run the Notebooks within 19_Algo_Proc_PCP/
   
   
* Week-12 **Reading** Chapters 14, 15, 18.  __Outcomes:__
  Mapping reductions. Also you get to appreciate the Church-Turing
  Thesis by also obtaining a taste of Lambda Calculus, aided
  by a Jove notebook that helps you read Chapter 18 selectively.
   - 23:11/15
     - Run the notebook within 20_Mapping_Redn/ and also do the
       practice problems within 20_Mapping_Redn/
       - This will give you practice with basic computability
       	 notions
       - This will also expose you to Lambda Calculus
     - Quiz-10 given; due 11/19 11:59pm, covers L23,24
     - Asg-10 given; due 11/24/21 11:59pm, covers L23,24
       (Post Correspondence, Mapping Reductions)
     
   - 24:11/17
     - Do the Practice Problems within 20_Mapping_Redn/
   
   
* Week-13 **Reading** Chapters 16, 17.  __Outcomes:__
  Basics of Boolean reasoning, conjunctive normal form
  formulae, validity versus satisfiability, NP-completeness.
   - 25:11/22
     - Run the Notebooks within 21_NPC_Lambda/
     - Quiz-11 given; due 11/26 11:59pm, covers L25,26
     - Asg-11 given; due FRIDAY 12/03/21 11:59pm, covers L25,26 
   - 26:11/24
     - Introduced the notion of NP-Completeness
   
   
* Week-14 **Reading** Chapters 16, 17. Begin reading Chapter 18. __Outcomes:__
  How mapping reduction looks in the area of NP-completeness proofs. Begin
  to understand Lambda Calculus.
   - 27:11/29
     - Run the Notebooks within 21_NPC_Lambda/
     - Quiz-12 given; due 12/3 11:59pm, covers L27,28

   - 28:12/1
     - Chapter 18 discussions
     
* Week-15 **Reading** Chapter 18.  __Outcomes:__  Learn the basics of
  Lambda calculus and show how it models programs.
   - 29:12/6
     - Review for Finals

   - 30:12/8
     - More review
   
* FINAL EXAM is on Canvas, Monday 12/13/20, 6:00pm - 8:00pm 
  
* -------------------------------------------------------
   

* Begin by running the notebook in 00_Overview_Of_CS3100_Fall2020/. Then start with the remaining directories such as
01_Computability_Languages/, 02_Basic_DFA/, etc.

* This is a directory prepared for the CS 3100, Fall 2021 students.

* It contains a description of how various Jove modules will be
  covered in our lectures.
  
* I'll now straight present the syllabus and the schedule of
  lectures. 
  
  - All Quizzes will be assigned on Canvas:
  
    - They are given out before a PAIR of lectures (occurring in a week).
    
    - They must be solved and submitted the same week Friday 11:59pm.
    
  - All our Assignments will be provided via Jove notebooks, with a PDF
    summarizing them as well. The PDF is kept on Canvas.
  
  - All our Exams (MT-1, MT-2 and Finals) will be given on Canvas.

  - **Practice problems** for the exams will be assigned each week, 
    but won't be graded. These will help you study for the exams
    in an incremental fashion. Find the Practice Problems on Canvas.

* CS 3100 is running in a *FLIPPED CLASS* style.

* You MUST run each Jove notebook mentioned below *BEFORE* you come
  to a lecture. These notebooks contain a video recording PLUS practice
  material for you.
  
* Some notebooks will last across multiple lectures, and some lectures
  will involve multiple notebooks.
  
* Assignments are to be turned in as finished Jove notebooks. There may
  also be uploads of other files, as specified.

* Each question of an assignment will be in a separate ".ipynb" Jove file.

* In some cases, we will allow documents to be scanned and uploaded as PDF. We require
  you to be using Adobe Scan - a free app you can get for iPhone or Android.

* For more info, see the PDF documents on Canvas that describe our course policies.


* -----------------------------------------------------------------

* **SYLLABUS** is as follows (if I write `` 1:8/25 '' it means Lec1 on 8/25, and so on)
* Some of the chapters are read across multiple weeks.

* -------------------------------------------------------

* QUIZ / ASG schedules

  - q1 8/23 - 27
  - a1 8/23 - 9/3

  - q2 8/30 - 9/3
  - a2 8/30 - 9/10

  - q3 9/6  - 9/17
  - a3 9/6  - 9/17

  - a4 9/13 - 9/24
  - q4 9/20 - 9/24

  - q5 9/29 - 10/6
  - a5 9/29 - 10/8

  - q6 10/6 - 10/11
  - a6 10/6 - 10/18

  - q7 10/18 - 10/22
  - a7 10/18 - 10/29

  - q8 10/25 - 10/29
  - a8 10/25 - 11/05

  - MT1 9/27 - 9/28

  - q9 11/01 - 11/05

  - MT2 11/06 - 11/08

  - a9 11/08 - 11/19

  - q10 11/15 - 11/19
  - a10 11/15 - 11/24

  - q11 11/22 - 11/26
  - a11 11/22 - 12/03

  - q12 11/29 - 12/03
  
  - Finals on 12/13 - 6:00 - 8:00 pm
* -------------------------------------------------------

