# PyConDE

## About

- Date: 11. - 17. July 2022
- Location: Dublin
- **submitted**

## Links

- [Website](https://europython.eu/)

## Biography

[Florian Bruhin](https://bruhin.software/) ("The Compiler") is a long-time
contributor and maintainer of both the [pytest](https://www.pytest.org/)
framework and various plugins. In 2013, he started the
[qutebrowser](https://www.qutebrowser.org) project, a keyboard-focused web
browser based on Python and Qt. In 2015, he discovered pytest - since then, he
has given talks and conducted workshops about pytest at various conferences and
companies.

- Company: Bruhin Software
- Position: Founder
- Twitter: @the_compiler
- Github: https://github.com/The-Compiler
- Homepage: https://bruhin.software

## Training
### Information

- Title: "**pytest - simple, rapid and fun testing with Python**"
- Length: 3h
- Track: Testing
- Domain Expertise: none *(none/some/expert/guru)*
- Python Skill Level: some *(none/some/expert/guru)*

### Abstract

*200-1500 chars*

The pytest tool presents a rapid and simple way to write tests for your Python
code. This training gives an introduction with exercises to some distinguishing
features. We'll also examine how to run existing non-pytest test suites and
discuss migration strategies. Various plugins which extend pytest's
functionality even further will be introduced. We'll finish with discussing
topics and questions of participants related to their own test suites and
usages.

### Tweet

The #pytest tool presents a rapid and simple way to write tests for your Python code. This training gives an introduction with exercises to some distinguishing features.

### Description

*300-5000 chars*

*The workshop uses Python 3.7 or later, it'd be good if you could set it up before the workshop starts. If you know how, set up a virtualenv with pytest installed - if you don't, that's no problem, I'll cover it at the beginning of the workshop! The material will apply to both pytest 6.2 and 7.x.*

This is the planned outline:

- (30 minutes) pytest feature walkthrough:
  * Automatic test discovery
  * Assertions without boilerplate via the assert statement
  * Configuration and commandline options
  * Marking and skipping tests
  * Data-driven tests via parametrization
  * Exercises / Live demos

- (60 minutes) pytest fixture mechanism:
  * Setup and teardown via dependency injection
  * Declaring and using function/module/session scoped fixtures
  * Using fixtures from fixture functions
  * Parametrizing fixtures
  * Looking at useful built-in fixtures (managing temporary files, patching, output capturing)
  * Advanced fixture features: Caching, cleanup, implicit fixture use
  * Exercises / Live demos

- (15 minutes): Running existing unittest suites with pytest:
  * Discussing advantages and limitations
  * Strategies for migrating to pytest

- (60 minutes): Plugin ecosystem:
  * Examples of available plugins
  * Property-based testing (automated testcase generation) via Hypothesis
  * Overview of useful plugins
  * Writing custom plugins (quick overview)
  * Various live demos

- (15 minutes): Open space for questions:
  * Leftover questions from the training
  * Other topics depending on interest
  * Buffer if we end up spending more time on something

**Basic Python OOP knowledge (e.g. what a class/instance is) is required.**

Note that the structure of the workshop is similar to the ones I've given at previous Europythons, but with updated material.

### Organizer Notes

Similar to previous trainings at Europython 2015, 2016, 2019 and 2021. Usually with a rather big (and happy) audience. Also submitted in a similar format to PyConDE and PyConIT. See my website for an overview: https://bruhin.software

### Reviewer Notes

Given previously at various conferences and companies, see https://bruhin.software/ for an overview.
