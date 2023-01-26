# FVOCA - Formal Verification of Critical Applications

## Course structure
This course teaches the main principles of Formal Verification of Software, with specific focus on applications that can be characterized as being critical computing applications.

<!-- 
1. The need for formal methods in critical system’s development
2. Real-time models: Timed Automata and Hybrid Automata, Temporal logic, static verification of programs using UPPAAL
3. Reasoning over requirements: First Order Logic, SAT and SMT solvers (including useful SMT theories), Automatic theorem proving using Z3, Dependent types and certified programming, Interactive theorem proving using Coq
4. Program verification: Design by Contract and Hoare Logic, Verification of programs using dedicated program verification frameworks, Runtime Verification.
 -->

1. __Mathematical Foundations__
  - Preliminaries:
      - Set Theory
      - Transition Systems
  - Propositional and First-Order logics: 
    - Syntax and Semantics
    - Natural Deduction
    - Automated Theorem Proving (SAT & SMT solving)

2. __Program Semantics__
  - Small Step and Big Step Operational Semantics
  - Hoare Logic's axiomatic semantics

3. __Reasoning over Programs__
  - SAT and SMT solvers 
  - _Automatic_ theorem proving using Z3
  - Introduction to _Interactive_ theorem proving using Coq


<!-- 
# Syllabus
 -->

## Material

### Slides

<ul>
  <li> <a href="slides/0-fvoca-intro.pdf">0. Introduction</a> </li>
  <li> <a href="slides/1-TA-modelling.pdf">1. Modelling with Timed Automata</a> </li>
  <li> <a href="slides/2-TA-verification.pdf">2. Verification of Timed Automata</a> </li>
  <!-- <li> <a href="slides/3-semantics.pdf">Formal Verification of Program Code</a> </li>
   -->
  <li> <a href="slides/3-semantics.pdf">3. A Not So Formal Introduction to Formal Verification of Program Code</a></li>
  <li> <a href="slides/4-semantics.pdf">4. Operational Semantics</a></li>
  <li> <a href="slides/5-hoare.pdf">5. Hoare Logic.pdf</a></li>
  <li> <a href="slides/6-hoare-vc.pdf">6. Hoare Logic and Verification Condition Generation I</a></li>
  <li> <a href="slides/7-hoare-vc-cont.pdf">7. Hoare Logic and Verification Condition Generation II</a></li>
  <li> <a href="slides/8-hoare-vc-ex.pdf">8. Hoare Logic and Verification Condition Generation III</a></li>
  <li> ... </li>
  <!-- <li> <a href="slides/_.pdf" class="hide">_</a></li> -->
</ul>


### Exercises and Assignments
<ul>
<!--   <li><a href="assignments/exercises1.pdf">Exercises on XYZ (individual)</a>
    <ul><li>
      <a href="assignments/helper1.pdf">Auxiliary notes</a>
    </li>
    </ul>
  </li>
 -->

 <li><a href="assignments/tp1.pdf">TP1: Specification and Verification in Uppaal (group)</a></li>
 <li><a href="assignments/tp2.pdf">TP2: Exercises about Hoare Logic and Verification Conditions Generation (not subject to evaluation)</a></li>
</ul>


<!-- 
### Useful links
 -->
<!-- - [Visual Paradigm](https://www.visual-paradigm.com) -->
<!-- 
- [mCRL2](https://www.mcrl2.org)
 -->
 <!-- - [Z3 in Python](https://ericpony.github.io/z3py-tutorial/guide-examples.htm) -->

<!-- 
### Bibliography
 -->
 <!-- - [__SysML Distilled: A Brief Guide (2013)__](https://www.amazon.com/SysML-Distilled-Systems-Modeling-Language/dp/0321927869),
  by Lenny Delligatti
  [![link to pdf](assets/img/PDF.png)](https://app.ute.edu.ec/content/4915-114-4-1-6-19/SysML%20Distilled_%20A%20Brief%20Guide%20-%20Lenny%20Delligatti.pdf)
 -->

<!-- 

- [__Reactive Systems: Modelling, Specification and Verification (2007)__](http://www.cambridge.org/us/academic/subjects/computer-science/programming-languages-and-applied-logic/reactive-systems-modelling-specification-and-verification"),
  by Luca Aceto et al.
  [![link to pdf](assets/img/PDF.png)](http://www.cs.ioc.ee/yik/schools/win2007/ingolfsdottir/sv-book-part1.pdf)

- [__Modeling and Analysis of Communicating Systems (2014)__](https://mitpress.mit.edu/books/modeling-and-analysis-communicating-systems),
  by Jan Friso Groote and Mohammad Reza Mousavi
  [![link to pdf](assets/img/PDF.png)](https://www.researchgate.net/publication/228689169_Modelling_and_analysis_of_communicating_systems)

-->


## Pragmatics


### Evaluation

 * __Final mark__ = Project (60%) + Exam (40%)

The project will be performed in groups of 2 students, addressing the practical aspects involving model checking and theorem proving, and will include some homework exercises. The exam will evaluate the student’s knowledge on the theoretical aspects.


### Deadlines

__Homework__  consists of a PDF report that must be submitted until Sunday @ 23:59 of the following week of being shown during lessons. For example, all exercises presented in the slides used in the week 8 Nov - 12 Nov must be submitted until Sunday 21 Nov.
__Assignments__ have specific deadlines, mentioned on their instructions.
The deadlines are summarised below, and may still suffer changes.

 - __20 Mar (Sun) @ 23:59__ - [Slides 1](slides/1-TA-modelling.pdf) (pages 1-37)
 - __27 Mar (Sun) @ 23:59__ - [Slides 1](slides/1-TA-modelling.pdf) (pages 37-end); [Slides 2](slides/2-TA-verification.pdf) (pages 1-19 except 8)  
 - __3 Apr (Sun) @ 23:59__ - [Slides 2](slides/2-TA-verification.pdf) (pages 8 and 20-end)  
 - __8 May (Sun) @ 23:59 (extended)__ - [TP1: Specification and verification in Uppaal](assignments/tp1.pdf)

### Lecturers

- [_David Pereira_](http://www.cister.isep.ipp.pt/people/david_pereira/),
  `drp arroba isep ponto ipp ponto pt`
- [_José Proença_](https://jose.proenca.org),
  `pro arroba isep ponto ipp ponto pt`
- [_Eduardo Tovar_](https://www.dei.isep.ipp.pt/~emt/),
  `emt arroba isep ponto ipp ponto pt`



 We will use a team in Microsoft Teams where all questions regarding this course unit should be placed, and where we can schedule virtual meetings if needed.

