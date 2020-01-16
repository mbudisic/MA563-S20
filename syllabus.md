---
title: MA563 Applied Dynamical Systems
description: 'Syllabus as taught in Spring 2020 by Dr. Marko Budišić, Clarkson University'
---

**Note: This syllabus is subject to change. All changes will be announced and discussed in class.**

{::options toc_levels="1..3" /}

1. TOC
{: toc style="font-size:10pt; column-count:3; column-width: 20px; column-gap: 20px;" }


## Instructor

Marko Budišić  --- office phone: (315-268-)3742 ---   <mbudisic@clarkson.edu> (put "MA563" in subject line somewhere)

 - Class Website: <https://mbudisic.github.io/MA563-S20> and on Moodle
 - Walk-in office hours: MWF 10-11.30a (90 min after class) in SC391
 - Other office hours available by e-mail appointment
 - Website: <http://people.clarkson.edu/~mbudisic>

## Summary of the class

This is a graduate class in applied dynamical systems. It can be thought of either as a continuation of MA533 (Graduate ODEs) or MA332 (Intermediate ODEs for Undergraduates).

It is intended as an introduction into topics of active research in applied dynamical systems. Therefore, the course is not one coherent whole, but a three-station sampling dinner intended on getting students' feet wet in several topics, but not wandering too deep in all of them.

By the end of the class, successful students will:

* have a basic vocabulary in **chaos theory**, **bifurcation analysis**, and **statistical description of dynamics**,
* be able to analyze model systems analytically, and explain where the interest in each of the topics arises in those systems,
* familiarize themselves with computational tools/approaches to studying each of the topics,
* explore the dynamical systems more deeply through a longer project.

A detailed breakdown of the topics is given in [on a separate page](./schedule.html).

## Topics and textbook

For each of the three topics, we will source the material from different books. Excerpts from the book will be provided through the closed Moodle webpage for the class. Buying ASY is likely a good idea if you're interested in dynamics in general; if your research is in bifurcations, then [BIF] is a good investment. If your research is in the last part, consult your advisor whether you should purchase a book.

### Chaos and maps:

What do we mean when we say that "dynamics is chaotic"? What is a "chaotic attractor"? What are the tools that make this "disordered" behavior into an ordered mathematics, that can be studied precisely.

* ASY Alligood, Kathleen T., Tim Sauer, and James A Yorke. 2010. Chaos : An Introduction to Dynamical Systems. New York, NY ; Springer,.

### Bifurcations

Often, dynamics of a phenomenon depend on a value of the parameter. Bifurcation theory describes what possible dynamics can arise when a parameter is changed, and what is ruled out.

* [BIF] Kuznetsov: "Elements of Applied Bifurcation Theory"
* [WIG] Wiggins: "Introduction to Applied Nonlinear Dynamical Systems and Chaos"

### Statistical description of dynamics

Instead of studying dynamics *geometrically* (trajectories as curves), one can study a collection (distribution) of many trajectories evolving side-by-side. The focus shifts from studying any one trajectory in geometric detail, to studying statistical properties of such distribution (mean, variance, etc.), and operators that represent how such distributions change.

* [LM] Lasota, Mackey: "Chaos, Fractals, Noise"
* [BOLLT] Bollt, Santitissadeekorn: "Applied and Computational Measurable Dynamics"



## Prerequisites

For some parts, we will rely on linear stability of differential equations, that is, analysis of the Jacobian eigenvalues and Floquet multipliers as covered in MA533 (Graduate ODEs). However, if you are unfamiliar with that material ASY has sufficient material in Section 7 that you would be able to catch up.

## Course work

### Participation

In class, you are expected to work on assigned problems, discuss, ask questions, and otherwise participate. If I notice that you haven't spoken in a while, I will call on you to answer a question. To prepare, read the assigned material/notes ahead of the class.

I expect you to attend all the lectures. If you are absent, please send me an e-mail with a heads-up. You may be additionally required to peer-grade projects or even some other assignments.

### Quizzes

Once per week, on Monday, there will be a quick 5 minute quiz at the beginning of the class. The purpose is to test the vocabulary/definitions from the previous week's material and the reading assigned for the Monday's class.

If you miss the class, there will be no way of making up the quiz. I will drop everyone's 3 lowest grades to allow for unexpected/unexcused absences.

### Homeworks

There will be at least 6 homeworks, requiring you to perform either pen-and-pencil calculations and computational analysis of some problems. **All homeworks are due in the last week of the semester.** You can submit them earlier though (as soon as you complete them), especially if you would like to have feedback on them ahead of the exams.

### Project

You will be expected to complete a longer project, either related to your research topic in dynamical systems (encouraged), or on a topic that would extend your understanding of dynamics.

There will be a list of suggested topics, but you're more than welcome to come up with your own. The only requirements are:

  * that the project relates to dynamical systems *in some way* (not necessarily to topics covered in class), and
  * that it involves some theoretical work (for example, justifying expectations for results of your computations, or setting a foundation for the code you're writing).

It is possible to propose a completely-theoretical project, but not a completely computational project.

*Deliverables*:

1. Mid-way through the semester, you will submit a **half-page typed proposal** of what your project will cover.
2. On the last day of class you will submit a **typed report on your project**. I will produce an official template that you will [clone using `git`](https://medium.com/@rvprasad/a-git-workflow-for-writing-papers-in-latex-4cfb31be4b06) and work on using either [Overleaf](https://www.overleaf.com/) or [local installation of LaTeX](https://www.latex-project.org/get/).
3. In the final week, likely during the official final exam timeslot, I will schedule time for us to meet and present **10-min project presentations** to the class.

**If you would like to [present your project at RAPS (Apr 17)](https://www.clarkson.edu/research-projects-showcase-raps), encouraged especially for students interested in dynamical systems, please let me know as early as you register that desire. You can definitely complete your project earlier in the semester, and then focus on the homeworks.**

### Exams

There will be an in-class midterm following each of the first two topics (Chaos, Bifurcations).

There will not be be a written final exam. Instead, we will have project presentations (see above).

### Tailored credit

What is tailored credit? It allows you to show committment to learning that is "tailored" to your personal way of working. Ways to earn it:

* classroom participation, by regularly asking questions that contribute to the discussions,
* projects, by working on a particularly challenging project, or delivering a particularly polished presentation (think conference-level),
* submitted work, by having tidy, comprehensive, detailed homeworks and/or exams,
* taking notes: if I have 2-3 volunteer notetakers, I will waive their requirement to do quizzes, and instead have them transcribe notes for the class in LaTeX for the full 10% of the grade, including tailored credit. This could go even higher, in case I have only 1 volunteer who wants to do all the notes, allowing you to even replace/augment some homework credit.

**Note:** tailored credit is something that requires a semester-long committment, not just a last-minute grade bump.

## Assessment

Each piece of work (homework, exam, project) will be scored on a 3 point scale.

  * 0 - not submitted/attempted
  * 1 - below expectation
  * 2 - meets standards
  * 3 - exemplary

To come up with the final grade, each category will be weighed according to the table below. The grade for the category will be a mean of grades of submitted work (e.g., grade for "Homework" will be a simple mean of all submitted homeworks). To come up with a final grade, I then expect that the nearest-integer rounding of the weighed score results in the letter grade. However, I do reserve the right to intervene in this simple formula if I noticed inflation of the grade, or particularly low-scores throughout.

| **Component**  | Quizzes | Homeworks | Exams | Project | Tailored Credit |
| **Percentage** | 5%  | 30% | 30% | 30% | 5% |


## Accommodations

I will do my best to arrange for any necessary accommodations that would enable you to fully participate in this class. If you require assistance during the lectures or during exams, please register with the [AccessABILITY Services](https://www.clarkson.edu/accessability-services).

**Student-Parents:** I know that many of our graduate students juggle their graduate school with being a good and present parent for their children. If you need to bring your child to work with you during a snow day (or for any other reason), they're welcome to sit in class and play while we work (providing they're not too loud). If you need any other arrangements made, please consult me - I am open to suggestions and will honor them, as long as they don't derail objectives (and objectivity) of the class.

## Ethical Behavior

From the Student Manual: _The Clarkson student will
not present, as his or her own, the work of another,
or any work that has not been honestly performed,
will not take any examination by improper means,
and will not aid and abet another in any dishonesty.
Failure to adhere to this code will mean a failing
grade and a report to the Dean of Students._

**Since this is a graduate class, I will be exceptionally strict regarding (un)ethical behavior.** I understand that different universities, professions, countries have different standard for ethical behavior. If you are not sure how to collaborate with your classmates in an ethical fashion, or how to use online resources, please consult me - there is no shame in asking.

In particular, your homeworks, midterms, or finals may be unsupervised, or take-home exams. During those exams, it will be incumbent upon your honor to use only allowed tools/notes, and not discuss the material with anyone else until you (and they) turn the work in.

The permission to use notes, textbook, etc. does not equal permission to copy from the textbook (verbatim). This constitutes plagiarism (even if the material use was allowed). Rather, rephrase, adapt the material from the reference text to suit the problem you are trying to solve, and in a way that demonstrates your understanding of the material.

## Additional Resources

### Other useful textbooks

*  Strogatz, Steven H. 2000. Nonlinear Dynamics and Chaos ;Steven H. Strogatz with Applications to Physics, Biology, Chemistry, and Engineering. Cambridge, Mass. : Westview,. [**Undergraduate book with many interesting applications and examples. Classic of the field.**]
*  Guckenheimer, John, and Philip Holmes. 1986. Nonlinear Oscillations, Dynamical Systems, and Bifurcations of Vector Fields. New york,. [**Long-time favorite book that covers many important topics.**]

### Non-technical books about the field

* Gleick, James. 1988. Chaos: Making a New Science. Penguin. [**Book that got me interested in this field.**]
* Diacu, Florin., and Philip Holmes. 1999. Celestial Encounters : The Origins of Chaos and Stability. Princeton, N.J. : Princeton University Press,. [**A wonderful read about Poincare's work.**]

### Community

SIAM Activity Group on Dynamical Systems is the primary community for applied dynamical systems. We maintain the [Dynamical Systems Web](https://dsweb.siam.org/) where you can get informed about the latest trends, software, and conferences on dynamics.

The largest conference is SIAM Conference on Applications of Dynamical Systems (SIAM DS), [held for many years in Snowbird, UT](https://www.siam.org/conferences/cm/conference/ds19), but now [moving to Portland, OR](https://www.siam.org/conferences/cm/conference/ds21).

### Should I join SIAM? Yes.

**What's SIAM again?** SIAM -- Society for Industrial and Applied Mathematics is the main professional society for most faculty and students at Clarkson's Department of Mathematics. [**Membership for our students is free**, so you should join right away (click here)](https://www.siam.org/Membership/Join-SIAM/Individual-Members/Student) (before the class begins).


{% include_relative abbrevs.md %}
