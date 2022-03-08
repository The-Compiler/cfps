# PyConDE

## About

- Date: 2. - 5. June 2022
- Location: Florence
- **submitted**

## Links

- [Website](https://pycon.it/en)

## Biography

[Florian Bruhin](https://bruhin.software/) ("The Compiler") is a long-time
contributor and maintainer of both the [pytest](https://www.pytest.org/)
framework and various plugins. In 2013, he started the
[qutebrowser](https://www.qutebrowser.org) project, a keyboard-focused web
browser based on Python and Qt. In 2015, he discovered pytest - since then, he
has given talks and conducted workshops about pytest at various conferences and
companies.

- Experience: Intermediate
- Previous talk link: https://youtu.be/cSJ-X3TbQ1c?t=15752

## Training
### Information

- Title: "**pytest - simple, rapid and fun testing with Python**"
- Length: 4h
- Topic: Python & Friends
- Audience Level: Beginner
- Tags: TDD, Best Practice, Development, Clean Code, Testing

### Abstract

*300 chars*

Using pytest, you can write tests in a rapid and simple way. This training gives an introduction with exercises to many of its features. We'll also explore how to migrate to pytest and see how it can run existing tests. Various plugins which extend pytest's functionality even further will be shown.

### Description

The pytest tool presents a rapid and simple way to write tests for your Python code. This training gives an introduction with exercises to some distinguishing features. We'll also examine how to run existing non-pytest test suites and discuss migration strategies. Various plugins which extend pytest's functionality even further will be introduced. We'll finish with discussing topics and questions of participants related to their own test suites and usages.

The workshop uses Python 3.6 or later, it'd be good if you could set it up before the workshop starts. If you know how, set up a virtualenv with pytest installed - if you don't, that's no problem, I'll cover it at the beginning of the workshop!

Rough planned outline:

- (15 minutes) Setup and overview
  * Why do we write tests? What different types/sizes of tests are there?
  * Installing pytest and getting things running

- (30 minutes) pytest feature walkthrough:
  * Automatic test discovery
  * Assertions without boilerplate via the assert statement
  * Configuration and commandline options
  * Marking and skipping tests
  * Data-driven tests via parametrization
  * Exercises

- (60 minutes) pytest fixture mechanism:
  * Setup and teardown via dependency injection
  * Declaring and using function/module/session scoped fixtures
  * Using fixtures from fixture functions
  * Parametrizing fixtures
  * Looking at useful built-in fixtures (managing temporary files, patching, output capturing)
  * Exercises

- (30 minutes): Running existing unittest suites with pytest:
  * Discussing advantages and limitations
  * Strategies for migrating to pytest
  * Using "autouse" fixtures in conjunction with XUnit-based setup/teardown methods
  * Exercises

- (30 minutes): Useful third-party plugins:
  * Coverage integration
  * Property-based testing (automated testcase generation) via Hypothesis
  * Overview of useful plugins

- (15 minutes): Mocking overview:
  * What tools can we use to deal with code which is in our way?
  * Avoiding mocking: Writing testable code
  * Avoiding mocking: Using the "real deal" via end-to-end tests

- (30 minutes): Writing custom plugins overview:
  * How are pytest plugins structured?
  * Example of some simple plugins

- (30 minutes): Open space for questions:
  * Interactively solving pytest integration problems on real-life projects as time permits

Basic Python OOP knowledge (e.g. what a class/instance is) is required.

### Organizer Notes

I've also given shorter and longer versions (1.5h/3h/1d/3d) at Europython, PyConDE, other conferences, and in companies. Usually the room ends up being pretty full. :)

See my website for an overview of past trainings: https://bruhin.software/
