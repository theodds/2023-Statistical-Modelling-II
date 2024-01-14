# SDS 383D

Welcome to SDS 383D for Spring 2022, a Ph.D.-level course on statistical modeling.  All course materials can be found through this GitHub page.

Some course logistics
- Instructor: Antonio Linero, <http://theodds.github.io>
- Meets: Mondays and Wednesday, 1:00 to 2:30 PM
- Classroom: UTC 4.120
- Office hours: Tuesday and Thursday, 1-2 PM, via Zoom (link on Canvas).

## Exercises

[You can find all the exercises here.](Notes/)  I'll post them as they become relevant throughout the semester.

## About the course

This course is about building probabilistic models for real-world systems. Our
approach will _primarily_, although not exclusively, be Bayesian.

Formally, this course has SDS 383C as a prerequisite. But plenty of students
have succeeded in the past without having taken that course. So here's a list of
substantive prerequisites. To succeed, you need to know the following topics:
- linear algebra
- how to perform basic data-analysis tasks in R or Python, at the level of
  Lessons 1-7 in [this undergraduate text](https://bookdown.org/jgscott/DSGI/).
- multivariable calculus. To be more specific, we lean often on gradients,
Hessians, and Jacobians, but not on more physics-relevant tools like divergence,
curl, Green's theorem, etc. 
- undergraduate probability (measure theory
isn't necessary). You should be comfortable writing down PDFs and understanding
what they mean. You should have seen moment-generating functions and the
change-of-variable formula involving Jacobians. 
- basic inferential statistics: sampling distributions, confidence intervals,
p-values, etc.
- basic regression, at the level of Lessons 14-15 of [this undergraduate
text](https://bookdown.org/jgscott/DSGI/)

If you have any doubt about your preparation for this course, feel free to chat
with me on the first day.

This is a blend between a traditional lecture-based course and a flipped
classroom. Some of the time is spend on lectures in class. But a lot of the
other class time is spent with you in charge. You will work on the [exercises
outside of class](Notes/). When you come to class, you will share what
you've done, and benefit from understanding what others have done. We will end
up covering less than in an exclusively lecture-based course. But what you
learn, you will learn deeply.

## Grading

Your grade consists of three pieces: 40% exercises, 40% final project, and 20%
participation.

### Exercises and In-Class Sessions

**Homework will be due on the first class day of each month.** To lighten the
burden, we will divide into groups of three each month (groups will not be
allowed to overlap in subsequent months). **Groups will be randomly selected to
present exercises for various problems, with code supporting code included,
throughout the semester.** At the end of each lecture, I will give a list of
homework problems that I may ask you to present a solution to during the
next lecture, but it is expected that you and your group will do all of the
exercises in the notes.

I will grade homework submissions in the following way: each month I will select
ten problems at random to grade. All parts of all problems will be weighted
equally so that, for example, if I graded Problem 1, Problem 2a, and Problem 2b,
then each of these would account for 1/3rd of the grade for the month. Each part
will be graded either 0/2, 1/2, or 2/2.

As far as how submissions should look:

1. For mathematics questions, I'm fine with you turning in hand-written
   solutions, provided that you answer the questions using complete sentences.
   Answers should not consist of just of long strings of calculations with no
   comments; you need to explain what you are doing.
   
2. For data analysis or coding questions, I expect results to be typed up with
   code given in-line and explained. It should be structured more-or-less like
   how I have things written up in the notes (i.e., code and discussion given
   together). The easiest way to do this would be to submit an R Markdown or
   Quarto document, or create a Jupyter notebook. If using one of these
   frameworks, you should submit both the compiled document as a pdf as well as
   the raw notebook/`.rmd`/`.qmd` document.

### Peer Evaluation

For each homework submission, you will give a grade to each of your group
members (including yourself) that reflects the grade that you would assign that
group member based on their contribution to the homework assignments and
in-class presentations, as well as any notes that you have about how the month
went. **This, in addition to participation in class, will be used to assign
participation credit.** This, in combination with the homework turned in, will be
used to assign a grade for the homework each month. **Note:** I will still have
final say on the grade each student gets on homework, and may overrule any
good/bad evaluations if I feel (and have evidence supporting) that the
evaluations are not representative of a student's contributions.

### Final project

Pick some relevant topic that interests you. Clear it with me ahead of time, and
then do it. Basically, I trust you to choose something that will optimize your
own learning experience, and that will dovetail with your research and
educational goals. It certainly can overlap with your own research. Examples:

1) Analyze a data set from your own research, using techniques from class or
closely related techniques.

2) Invent a new technique and show how awesome it is.

3) Prove something interesting about a procedure or algorithm related to what
we're studying (admittedly unlikely, but certainly possible!)

4) Read a paper, or a group of related papers, that expands on some topic we've
covered in class. Implement the method(s) and benchmark it (them) against
something else.

Final projects are due on the day of the university-scheduled exam: Friday, May
4th.

Note: you should feel free to work either solo or in pairs for the projects.

## Programming Requirements

We will use `R` and `RStudio` in class. Because of the group-work aspect of this
class, and the fact that we will be presenting solutions, it is important that
we all have at least the language in common, so I won't accept code written in
other languages. Sorry!

**I am happy to assist with programming issues, especially if you haven't used
`R` before, but it is your responsibility to either learn this material on your
own or reach out to me for help if you are struggling.**

## Topics

Here's a partial list of topics that we'll cover.

- Generalized linear models (GLMs)
- The parametric and nonparametric bootstraps
- Robust inference with semiparametric and dependent data
- Hierarchical models and multi-level regression
- The multivariate normal distribution
- Function estimation (nonparametric regression, density estimation, etc)

There are no formally required textbooks, but here are three recommended references:

- [Data Analysis Using Regression and Multilevel/Hierarchical
  Models](http://www.stat.columbia.edu/~gelman/arm/), by Andrew Gelman and
  Jennifer Hill. An e-book version is available through the [UT Library
  website](http://www.lib.utexas.edu).
- _Generalized Linear Models_ by McCullagh and Nelder
- _All of Statistics_ by Larry Wasserman.
