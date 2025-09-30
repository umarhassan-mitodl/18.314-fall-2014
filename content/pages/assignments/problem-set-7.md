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
title: Problem Set 7
uid: cff149ed-cd85-f47e-d1ab-bc1193f10c61
---
Most of the problems are assigned from the required textbook Bona, Miklos. *A Walk Through Combinatorics: An Introduction to Enumeration and Graph Theory*. World Scientific Publishing Company, 2011. ISBN: 9789814335232. \[Preview with [Google Books](http://books.google.com/books?id=TzJ2L9ZmlQUC&pg=PAfrontcover)\]

A problem marked by \* is difficult; it is not necessary to solve such a problem to do well in the course.

## Problem Set 7

- Due in Session 19
- Practice Problems
    - Session 17: None from textbook
        - Let *n*≥1, and let *f*(*n*) be the number of partitions of *n* such that for all *k*, the part *k* occurs at most *k* times. Let *g*(*n*) be the number of partitions of *n* such that no part has the form *i*(*i*+1), i.e., no parts equal to 2, 6, 12, 20, …. Show that *f*(*n*)=*g*(*n*). Use generating functions.
        - Let *f*(*n*) denote the number of partitions of *n* with an even number of 1's. Give a combinatorial proof and a generating function proof that *f*(*n*) + *f*(*n*\-1) = *p*(*n*), the total number of partitions of *n*.
    - Session 18: Chapter 8: Exercises 20, 21
- Problems Assigned in the Textbook
    - Chapter 8: Exercises 27, 28, 32, 37\*. In exercise 28, you can ignore the last sentence (about comparing with Exercise 4). **Hint** for 37. Consider the product 1/(1-*qx*)(1-*qx*²)(1-*qx*³)…
- Additional Problems
    - (A8\*) Show that the number of partitions of *n* for which no part appears exactly once is equal to the number of partitions of *n* for which every part is divisible by 2 or 3. For instance, when *n*\=6 there are four partitions of the first type (111111,2211,222,33) and four of the second type (222, 33, 42, 6). Use generating functions.
    - (A9) Show that the number of partitions of *n* for which no part appears more than twice is equal to the number of partitions of *n* for which no part is divisible by 3. For instance, when *n*\=5 there are five partitions of the first type (5, 41, 32, 311, 221) and five of the second type (5, 41, 221, 2111, 11111). Use generating functions.
- Bonus Problems
    - (B2) Find the generating function *G*(*x*) = Σ{{< sub "_n_≥0" >}} anxn/*n*!,      
        where *a*{{< sub "_n_+1" >}} = (*n*+1)*a*{{< sub "_n_" >}}\-{*n*\\choose 2}*a*{{< sub "_n_\-2" >}} for *n*≥0, and *a*{{< sub "0" >}}\=1.       
        Thus *a*{{< sub "1" >}}\=1, *a*{{< sub "2" >}}\=2, *a*{{< sub "3" >}}\=5. You don't need to find a formula for *a*{{< sub "_n_" >}}.