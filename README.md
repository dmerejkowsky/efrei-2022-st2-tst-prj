# ST2 Software Testing Project for EFREI (2022 edition)

## Introduction

This repository contains all the information you need to complete the
project for EFREI.

It will be updated from time to time, you're advised to watch changes made
in this repository.

## Rules

* Be nice!
* Tell me when you think something is wrong
* No plagiarism. You can use code written by someone else, but in that case, make it clear when it comes from (URL if you find it online, name of the team/person if you borrowed the code from an other team)


## Overview

You will be using a web application (Human Relations Database Manager), or hr-db for short.

There a 16 instances deployed on `https://hr.dmerej.info` - each team has its own instance. Please only use your instance!

Each instance shares the same code, and the production code is intentionally buggy (at least 3 bugs, probably more ...)

During the project, you will be testing the web application using various techniques:

* Black-box testing: designing and running test plans by hand
* Acceptance testing: writing end-to-end tests using selenium or playwright
* Unit testing: when you'll have access to the source code

## Grading

There will be several kind of deliveries:

* A log
* Test code
* Other deliveries, depending on the sessions

The log will be graded on:

* readability
* how much you put things into perspective

The test code will be graded:

* quality of the code - test code should be easy to read, write and maintain
* coverage of the test code

The deliveries will be graded on how much you followed the specifications

## Specifications for the HR database

* Every field concerning the Employee information is mandatory
* The zip code of any address should be an integer

## Session 1

*Note: as an exception to the rule, you should not interact with other
teams during this session. I want to see how many bugs you can find by
yourselves without any indication.*


### Design a test plan.

At the minimum, a test plan should contain:

* a template with the lists of tests
* several "runs", each generated from the template, each containing a date and the outcome of the tests

### Run the test plan

Once the test plan has been written, use all members of the team to perform a run, running the tests by hand on your instance.

Find as many bugs as possible.

### Add bugs to a bug tracker

1. Set up a bug tracker. You may use the built-in issue tracke of GitHub or GitLab
2. Add all the bugs you found during the first run of the test plan to the tracker
3. Send me the bug tracker link by email

## Session 2

1. Wait for the next release of the web application.
2. Run a second test plan
3. Update the bug tracker accordingly
4. Send me the bug tracker link by email
