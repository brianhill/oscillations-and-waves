# Oscillations and Waves in Mathematica
## *An Introduction to Programming, Numerical Methods, and the Physics of Oscillations and Waves

*Unofficial/Short Course Title:* Oscillations and Waves

*Spring 2025, Deep Springs College, [Prof. Brian Hill](https://brianhill.github.io)*

## Syllabus

* A PDF of the [Syllabus](./OscillationsAndWavesSyllabus.pdf) (containing the same information as is on these web pages).

## Daily Schedules (Kept Retrospectively)

* [Daily Schedule Term 4](./daily_schedule_term_4.html)
* [Daily Schedule Term 5](./daily_schedule_term_5.html)

## Required Resources

### Computing Resources

* Mathematica license: Desktop and Cloud is $75/year for a student. There is also a semester (six-month) plan for $50, and even a monthly plan, for $10/month, which would work fine and save you another $10 if you only used it for the four months from early-January to early-May.
* You need a laptop on which you can install of Mathematica. Disk space is critical: 18 GB is required if you install the local documentation. 9 GB is tight but doable without local documentation.

### Texts

The text we will start off with is freely available on-line, so you do not need a physical copy:

* Stephen Wolfram, *An Elementary Introduction to the Wolfram Language, 3rd Edition,* Wolfram Media, Inc., 2023 ([Online version](https://www.wolfram.com/language/elementary-introduction/3rd-ed/index.html.en)), hereafter abbreviated *EIWL3*.

If you want a physical copy, get the 3rd edition ([Amazon link](https://www.amazon.com/Elementary-Introduction-Wolfram-Language/dp/1944183078)).

For the numerical methods and the physics theory, I will prepare handouts and Mathematica notebooks for you to download and modify.

## Overview

### The First Course within the Course

In order to do mathematical modeling, we need to learn a serious programming language, and we will use Mathematica for this purpose. Mathematica is a program that you interact with using the &ldquo;Wolfram Language.&rdquo; We will learn the language by studying the entirety of *EIWL3.* The printed edition is over 300 pages divided into 48 sections. We will do 2-3 sections per class, and by the end of the book, you will be in an extremely good position to apply Mathematica to any problem that interests you. In parallel with learning the language we will be learning oscillatory motion and then waves and the numerical methods required to model them on a computer. That is the second course within the course, and where things get most interesting.

### The Second Course within the Course

What we will do with Mathematica in this course is fundamental physics that all theoretical physicists know very well: oscillatory motion and waves. After we deal with constant motion and constant acceleration, we will animate simple oscillation of a single particle. The classic physical system that exhibits simple oscillation is [a mass hanging from a spring](https://youtu.be/I_Wscia8h9I). There is a significant increase in complexity when you graduate from an idealized spring obeying Hooke&rsquo;s Law to putting the mass on the end of a pendulum rod: the simple system becomes non-linear.

The next level of complexity is to step it up to two particles. If the two particles are connected, even weakly connected, this leads to surprising behavior (resonant exchange of energy) that was not present for either particle separately. The most common example is known as the coupled pendulum. Since Kel asked about chaos (not something I have much familiarity with), I will see if we can code up some chaotic motion using the compound pendulum (and note that the compound pendulum is not the same as the coupled pendulum).

Yet another level of complexity is to step it up to from two to *N* particles. After we get quite familiar with the behavior of *N* particles, where *N* is a modest number like 10 or 32, we will take the limit that *N* goes to infinity! Waves appear! They appear completely naturally from laws governing a finite but ever larger number of ever more closely spaced and ever smaller particles.

Waves first show up in a single dimension, such as waves on a musical instrument string, where each element of the string has a position, but the string itself is treated as a one-dimensional object (specified by a mass per unit length and a tension), that can vibrate in the two directions perpendicular to its length. Then we can step up the complexity yet again and consider waves in two dimensions, such as waves on square and round drumheads.

Finally the highest level of complexity we can hope to get to in a one-semester course, starting with no significant prerequisites, is to model quantum-mechanical waves in one and more dimensions. The study of three-dimensional electron waves around an atomic nucleus requires some decently advanced manipulation of differential equations, but by the end of our course, you will start having sufficient intuition about such equations and their solutions that we can make some headway and by the final class, explore the s, p, d, and f Hydrogen wave functions, and even the modulation of spherical harmonics by radial wave functions.

## Grading

* 45% assignments
* 37.5% exams 15% for each of the first two exams (on physical modeling and numerical methods), and 7.5% for a third (shorter) exam focused on the Wolfram language itself
* 7.5% final project presentations during Weeks 12 and 13 of the semester.
* 10% preparation for class and leadership of course

## Problem Sets / Handouts / Exams

There will be assignments in *EIWL3* due almost every class, limited only by how quickly I can plan and grade them. The more problems you do, the more fluent you will be with the Wolfram language. In addition to the problem sets and their solutions, there will be handouts on numerical methods and physics modeling, and the exams which will be delivered as Mathematica notebooks.

Problem sets will generally be turned in by email using Mathematica notebooks. The last step in your process before you submit a notebook as your solution is to quit the Mathematica kernel, and then re-execute your entire notebook with a fresh kernel. Assuming your notebook executes reproducibly and without error with a fresh kernel, you have something you can turn in. If it doesn't execute reproducibly and without error, find and fix the problems, and repeat this process until it does.

## Absences (and late work)

The College's policies on absences (and late work) are applicable. Refer to the Academic Year 2024-2025 Deep Springs Handbook.
