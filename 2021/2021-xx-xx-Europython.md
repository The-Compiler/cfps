# Europython 2019

## About

- Date: 26. July - 1. August 2021
- Location: online
- **submitted**

## Biography

Florian Bruhin ("The Compiler") is a long-time contributor and maintainer of
both the pytest framework and various plugins. He discovered pytest in 2015 -
since then, he has given talks and conducted workshops about pytest at various
conferences and companies. His primary project, qutebrowser (a keyboard-focused
web browser), has grown from a hobby to a donation-funded part-time job.

## Training
### Information

- Title: "**Introduction to pytest**" *(max 80 chars)*
- Subtitle: **Simple, rapid and fun testing with Python**
- Length: 1.5h
- Python skill level: Intermediate
- Domain Expertise: Beginner
- Tags: Test Libraries, Testing

### Abstract (longer version)

The pytest tool presents a rapid and simple way to write tests for your Python code. This training gives an introduction with exercises to some distinguishing features. We'll also examine how to run existing non-pytest test suites and discuss migration strategies. Various plugins which extend pytest's functionality even further will be introduced. We'll finish with discussing topics and questions of participants related to their own test suites and usages.

The workshop uses Python 3.6 or later, it'd be good if you could set it up before the workshop starts. If you know how, set up a virtualenv with pytest installed - if you don't, that's no problem, I'll cover it at the beginning of the workshop!

This is the planned outline:

- (30 minutes) pytest feature walkthrough:
* Automatic test discovery
* Assertions without boilerplate via the assert statement
* Configuration and commandline options
* Marking and skipping tests
* Data-driven tests via parametrization
* Various live demos

- (60 minutes) pytest fixture mechanism:
* Setup and teardown via dependency injection
* Declaring and using function/module/session scoped fixtures
* Using fixtures from fixture functions
* Parametrizing fixtures
* Looking at useful built-in fixtures (managing temporary files, patching, output capturing)
* Advanced fixture features: Caching, cleanup, implicit fixture use
* Various live demos

- (30 minutes): Running existing nose/unittest suites with pytest:
* Discussing advantages and limitations
* Strategies for migrating to pytest
* Using "autouse" fixtures in conjunction with XUnit-based setup/teardown methods

- (30 minutes): Useful third-party plugins:
* Examples of available plugins
* Property-based testing (automated testcase generation) via Hypothesis
* Overview of useful plugins
* Writing custom plugins (quick overview)
* Various live demos

- (30 minutes): Open space for questions:
* Leftover questions from the training
* Other topics depending on interest
* Buffer if we end up spending more time on something

Note that the structure of the workshop is similar to the ones I've given at previous Europythons (2015, 2016 and 2019), but with updated material and adjusted for a more remote format.
