# Data Club on GitHub Actions - Simple example

> by Henry Webel from the Data Science Platform at DTU biosustain

## Pre-requisites

- GitHub account: [github.com/signup](https://github.com/signup)

## Annoucement
GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform 
that helps you to automate your build, testing, and deployment pipeline. Therefore, it 
makes sure your software remains reliable by catching bugs or dependency conflicts whenever 
your code (or its dependencies) change. It also helps you avoid accidentally skipping 
important checks that you would normally perform manually.

We will focus on introducing the core concepts of workflows and jobs in a hands-on manner 
using a simple hello-world example. We will also show some more elaborated examples as an 
outlook for interested users. Prerequisite is that you have a GitHub account and 
some familiarity with the command line. We do the tutorial on GitHub Codespaces using VSCode(see intro).

It will make most sense to attend if you want to use GitHub Actions (or similar on GitLab 
or BitBucket) on repositories where you maintain your package or analysis code. 
After this Data Club, it will be easier for you to implement basic automated checks, 
- e.g. format checkers or lint checkers - for catching common errors or pitfalls on your code.

## Agenda
 
Date 30th April, 10-12 am
- 10:00 - 11:20 Github actions including theory and hands-on
- 11:20 - 12:00 Sandwiches and networking

Location: building 208 – room 002 (ALC3)

## Content of the tutorial (this repository)

A simple example of a GitHub Action workflow that run command line commands.


## Extended example

Check out my Python package template for a more evolved example:

- [python package template](https://github.com/RasmussenLab/python_package)

Or have a look at our VueGen repository for a live project with continoues integration and
deployment using GitHub Actions.
- [VueGen](https://github.com/Multiomics-Analytics-Group/vuegen)
