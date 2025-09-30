---
content_type: page
description: This page provides a problem set on combinatorial analysis.
draft: false
learning_resource_types:
- Assignments
ocw_type: CourseSection
parent_title: Assignments
parent_type: CourseSection
parent_uid: 88f36882-0870-1a5b-07ed-2e929d68ddce
title: Problem Set 8
uid: d79065de-b3ec-e190-b0f6-ecff98e8ba65
---
Most of the problems are assigned from the required textbook Bona, Miklos. *A Walk Through Combinatorics: An Introduction to Enumeration and Graph Theory*. World Scientific Publishing Company, 2011. ISBN: 9789814335232. \[Preview with [Google Books](http://books.google.com/books?id=TzJ2L9ZmlQUC&pg=PAfrontcover)\]

A problem marked by \* is difficult; it is not necessary to solve such a problem to do well in the course.

## Problem Set 8

- Due in Session 22
- Practice Problems
    - Session 19: None from textbook
        - A group of *n* children form circles by holding hands, with a child in the center of each circle. Let *h*(*n*) be the number of ways that this can be done. Set *h*(0)=1. Find a *simple* expression for the generating function *F*(*x*) = Σn≥₀*h*(*n*)xⁿ/*n!.* A circle may consist of just one child holding his or her own hands, but a child must be in the center of each circle. The clockwise order of the children around the circle matters, so *k* children can form a circle in (*k*\-1)! ways. Thus *h*(1)=0, *h*(2)=2, *h*(3)=3, *h*(4)=20, *h*(5)=90. Answer: (1-*x*)ˣ
    - Session 20: Chapter 9: Exercises 1, 2, 3, 6, 16, 18
    - Session 21: Chapter 9: Exercises 8, 11, 14, 21
- Problems Assigned in the Textbook
    - Chapter 9: Exercises 24, 30
    - Chapter 9: Exercises 34, 41. **Hint** for 41: Induction on *n*.
- Additional Problems
    - (A10) Let *f*(*n*) be the number of ways to paint *n* giraffes either red, blue, yellow, or turquoise, such that an odd number of giraffes are red and an even number are blue. Use exponential generating functions to find a simple formula for *f*(*n*). (It is allowed to have no giraffes painted blue, yellow, or turquoise.)
    - (A11) Let *f*(*n*) be the number of ways to partition an *n*\-element set, and then to choose a nonempty subset of each block of the partition. Find a simple formula (no infinite sums) for the exponential generating function *G*(*x*) = Σ{{< sub "_n_≥0" >}} *f*(*n*)*x\_*{{< sup "n" >}}*/\_n*!.
    - (A12) Give a simple reason why a 9-vertex simple graph cannot have the degrees of its vertices equal to 8, 8, 6, 5, 5, 4, 4, 3, 1.
- Bonus Problems
    - Chapter 9: Exercise 49