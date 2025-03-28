# Oscillations and Waves in Mathematica

*Unofficial/Short Course Title:* Oscillations and Waves

*Spring 2025, Deep Springs College, [Prof. Brian Hill](https://brianhill.github.io)*

## Preliminary Syllabus

* A PDF of the [Preliminary Syllabus](./OscillationsAndWavesPreliminarySyllabus.pdf) which contains essentially the same information as is on this web page, but which I don't wordsmith and update quite as frequently.

## Daily Schedules (Kept Retrospectively)

* [Daily Schedule Term 4](./daily_schedule_term_4.html)
* [Daily Schedule Term 5](./daily_schedule_term_5.html)

## Required Resources

### Computing Resources

* Mathematica license: Desktop and Cloud is $75/year for a student. There is also a semester (six-month) plan for $50, and even a monthly plan, for $10/month, which would work fine and save you another $10 if you only used it for the four months from early-January to early-May.
* You need a laptop on which you can install of Mathematica. Disk space is critical: 18 GB is required if you install the local documentation. 9 GB is tight but doable without local documentation.
* For further details on required computing resources, see email to the entire community sent Dec. 15th, and Andy and David's Dec. 16th follow-ups.

### Texts

The text we will start off with is freely available on-line, so you do not need a physical copy:

* Stephen Wolfram, *An Elementary Introduction to the Wolfram Language, 3rd Edition,* Wolfram Media, Inc., 2023 ([Online version](https://www.wolfram.com/language/elementary-introduction/3rd-ed/index.html.en)), hereafter abbreviated *EIWL3*.

If you want a physical copy, get the 3rd edition ([Amazon link](https://www.amazon.com/Elementary-Introduction-Wolfram-Language/dp/1944183078)).

For the physics theory, I will prepare handouts.

## Overview

### The First Course within the Course

In order to do mathematical modeling, we need to learn a serious programming language, and we will use Mathematica for this purpose. Mathematica is a program that you interact with using the &ldquo;Wolfram Language.&rdquo; We will learn the language by studying much, if not all, of *EIWL3.* The printed edition is over 300 pages divided into 48 sections. If we do 2-3 sections a class we can do most of the material up to Section 40 during Term 4, at which point you will be in an extremely good position to apply Mathematica to any problem that interests you. In parallel with learning the language we will be learning oscillatory motion and then waves. That is the second course within the course, and where things get most interesting.

### The Second Course within the Course

What we will do with Mathematica in this course is fundamental physics that all theoretical physicists know very well: oscillatory motion and waves. After we deal with constant motion and constant acceleration, we will animate simple oscillation of a single particle. The classic physical system that exhibits simple oscillation is [a mass hanging from a spring](https://youtu.be/I_Wscia8h9I). There is a significant increase in complexity when you graduate from an idealized spring obeying Hooke&rsquo;s Law to putting the mass on the end of a pendulum rod: the simple system becomes non-linear.

The next level of complexity is to step it up to two particles. If the two particles are connected, even weakly connected, this leads to surprising behavior (resonant exchange of energy) that was not present for either particle separately. The most common example is known as the coupled pendulum. Since Kel asked about chaos (not something I have much familiarity with), I will see if we can code up some chaotic motion using the compound pendulum (and note that the compound pendulum is not the same as the coupled pendulum).

Yet another level of complexity is to step it up to from two to *N* particles. After we get quite familiar with the behavior of *N* particles, where *N* is a modest number like 10 or 32, we will take the limit that *N* goes to infinity! Waves appear! They appear completely naturally from laws governing a finite but ever larger number of ever more closely spaced and ever smaller particles.

Waves first show up in a single dimension, such as waves on a musical instrument string, where each element of the string has a position, but the string itself is treated as a one-dimensional object (specified by a mass per unit length and a tension), that can vibrate in the two directions perpendicular to its length. Then we can step up the complexity yet again and consider waves in two dimensions, such as waves on square and round drumheads.

Finally the highest level of complexity we can hope to get to in a one-semester course, starting with no significant prerequisites, is a taste of what quantum-mechanical waves look like in three dimensions. The study of three-dimensional electron waves around an atomic nucleus requires some decently advanced manipulation of differential equations, but by the end of our course, perhaps you will start having sufficient intuition about such equations and their solutions that we can make some headway. Even if we only get to round drumheads &mdash; or even just to square drumheads which are a little simpler than round ones &mdash; your intuition for the solutions of partial differential equations will be getting strong.

## Grading

* 45% assignments
* 15% (45% total) for each of three exams, dates to be determined, but coming at about the 5th, 9th, and 14th week of classes
* 10% preparation for class and leadership of course

## Problem Sets / Handouts / Exams

There will be problem sets due at least every week, and sometimes every class, limited only by how quickly I can assign them, write solutions, and grade. The more problems you do the better. In addition to the problem sets and their solutions, there will be handouts, exams, and exam solutions to file. Locate a three-ring binder and a three-ring hole punch, and file everything chronologically. Actually, reverse-chronological is the most convenient, because you then naturally open your binder to what you are currently working on.

Problem sets will generally be turned in by email using Mathematica notebooks. The last step in your process before you submit a notebook as your solution is to quit the Mathematica kernel, and then re-execute your entire notebook with a fresh kernel. Assuming your notebook executes reproducibly and without error with a fresh kernel, you have something you can turn in. If it doesn't execute reproducibly and without error, find and fix the problems, and repeat this process until it does.

## Absences (and late work)

The College's policies on absences (and late work) are applicable. Refer to the Academic Year 2024-2025 Deep Springs Handbook.
