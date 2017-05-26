---
layout: tutorial
title: Day 1
permalink: /day-1
---

Welcome to day 1! The first day will focus on making sure everyone is on the same page regarding the syllabus, deliverables, small group assignment and other administrative details.  We will also make sure you are up and running with R, RStudio, and Slack.



## Tutorials & Resources

Please read & work through the following prior to our first class. 

### Syllabus

If you have not already done so, be sure to read through the syllabus for your section [[OPER-682]](oper682) [[LOGM-682]](logm682) so that you understand the structure of my classes, the tentative schedule, grading policies, and other pertinent details.

### Communication

[Slack](https://slack.com/) will replace e-mail and Blackboard for our course. You will receive an invitation to the [AFIT R slack team](). You may wish to install one of the [apps](https://slack.com/downloads/osx). Read this [introduction to Slack](https://vimeo.com/133692325) from one of Kris Shaffer’s courses (although this is a completely different course and slack team it provides a nice introduction that you might find useful).  If you have any questions or concerns your first step should be going to our [slack channel]() and posting your issue.  You and your classmates should be monitoring slack to help each other out. In addition, I will also be watching slack and will chime in when necessary but my hope is that this will be a social process where everyone contributes to knowledge advancement.

### Intro to Data Science

- Read about the [Role of Data Wrangling](http://uc-r.github.io/why_wrangle)

### Intro to R

- Work through the [Introduction to R](intro).
- Work through the [R Basics tutorial](http://uc-r.github.io/section2_basics) to install R and RStudio and (re-)familiarize yourself with the basic functionality of the programming language.


## Deliverables

Create a .R script titled "day-1.R" and in this script perform the following exercises:

- compute $$100(1 + \frac{0.05}{12})^{24}$$
- what is the remainder when 3333 is divided by 222?
- investigate the behavior of $$(1 + \frac{1}{n})^n$$ for large, integer values in *n*.
- the Economic Order Quantity (EOQ) gives the optimal order quantity as $$Q = \sqrt{\frac{2DK}{h}}$$ where *D* is the annual demand, *K* is the fixed cost per order, and *h* is the annual holding cost per item. Create and set the variables $$D = 1000$$, $$K = 5$$, and $$h = 0.25$$ and compute the associated value of Q.
- for an initial principal amount *P* and a nominal annual interest rate *r* that is compounded *n* times per year over a span of *t* years, the final value of a certificate of deposit is $$F = P(1 + \frac{r}{n})^{nt}$$. Create and set the variables $$P = 100$$, $$r = 0.08$$, $$n = 12$$, and $$t = 3$$ and compute the associated value of *F*.

See you in class!

## Class

**1\. Lecture:** In today's lecture we are going to create an automated R Markdown report. Please download this material: &nbsp; <a href="https://www.dropbox.com/sh/fs9qnoz09n7on8c/AAApAUBtf3EMGTpA-dWJ6KQea?dl=1" style="color:black;"><i class="fa fa-cloud-download" style="font-size:1em"></i></a>

**2\. Group Work:** Each of you have been psuedo-randomly assigned to a group (psuedo because your skill level influenced the random order); you can find your group number [here](https://docs.google.com/spreadsheets/d/1cWKlik99wuYsGMrCKLDNZm09efuZml-GmIc5DrhTRSI/edit?usp=sharing). Working with your groups I want you to turn your homework assignment, which should look something like [this](http://rpubs.com/bradleyboehmke/datawrangling_week1_homework) into a presentation format that looks like [this](https://rpubs.com/bradleyboehmke/week1_gw). You may want to consult the links provided at [http://uc-r.github.io/r_markdown#presentations-slides](http://uc-r.github.io/r_markdown#presentations-slides) for available options.  Each student should produce their own presentation; however, leverage your group to help each other. If you complete this and have available time, work with your small group to re-produce this [HTML file](https://rpubs.com/bradleyboehmke/rmarkdown_replication).