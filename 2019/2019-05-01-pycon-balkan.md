# PyCon Balkan

## About

- Date: 3. - 5. October 2019
- Location: Hilton Belgrade, Serbia
- **submitted**

## Timeline

- CfP open: 15. April 2019
- CfP closing: 15. July 2019

## Links

- [Website](https://pyconbalkan.com/)
- [CfP Infos](https://pyconbalkan.com/cfp)
- [CfP Submission](https://sessionize.com/pycon-balkan-2019/)

## Speaker info

- Previous talks: https://www.youtube.com/watch?v=rCBHkQ_LVIs
- Speaker tagline: qutebrowser BDFL, pytest lover

### Speaker biography

Florian Bruhin ("The Compiler") is a long-time contributor and maintainer of
both the pytest framework and various plugins. In 2013, he started the
qutebrowser project, a keyboard-focused web browser based on Python and Qt. In
2015, he discovered pytest - since then, he has given talks and conducted
workshops about pytest at various conferences and companies.

Tagline: qutebrowser BDFL, pytest fan

## Training
### Information

- Title: "**pytest - simple, rapid and fun testing with Python**"
- Length: 90-180 min
- Level: Intermediate
- Tags: Tools, Framework
- Session format: Workshop

### Description

The pytest tool presents a rapid and simple way to write tests for your Python
code. This training gives an introduction with exercises to some
distinguishing features. We'll also examine how to run existing non-pytest test
suites and discuss migration strategies. Various plugins which extend pytest's
functionality even further will be introduced.

This is the planned outline:

- (30 minutes) pytest feature walkthrough:
  * Automatic test discovery
  * Assertions without boilerplate via the assert statement
  * Configuration and commandline options
  * Marking and skipping tests
  * Data-driven tests via parametrization
  * Exercises

- (30 minutes) pytest fixture mechanism:
  * Setup and teardown via dependency injection
  * Declaring and using function/module/session scoped fixtures
  * Using fixtures from fixture functions
  * Parametrizing fixtures
  * Looking at useful built-in fixtures (managing temporary files, patching, output capturing)
  * Exercises

- (15 minutes): Running existing unittest suites with pytest:
  * Discussing advantages and limitations
  * Strategies for migrating to pytest
  * Exercises

- (15 minutes): Useful third-party plugins:
  * Coverage integration
  * Property-based testing (automated testcase generation) via Hypothesis

Basic Python OOP knowledge (e.g. what a class/instance is) is required.

### Reviewer Notes

The above outline is for a 1.5h version, I'd be happy to give a 3h version
instead if desired.

I've given similar workshops at Europython 2015 and 2016. They were visited by
many attendees and I've received good feedback. Additionally, I've conducted
longer (3-day) workshops about pytest/tox/devpi in various companies, see e.g.:
https://www.python-academy.com/courses/specialtopics/python_course_testing.html

Those workshops weren't recorded, and I haven't given many talks yet - for an
example, see my talk at the Swiss Python Summit 2016 (note that the video is
rather old and I've done some more speaking/workshops since then, but nothing I
could find a recording of):
https://www.youtube.com/watch?v=rCBHkQ_LVIs

## Talk
### Information

- Title: "**Testing Qt GUI applications with pytest**"
- Length: 30 minutes (25 minutes + 5 minutes Q/A)
- Level: Advanced
- Tags: Tools, Framework
- Session format: Talk

### Description

Both PySide and PyQt allow rapid prototyping and development of Qt GUI
applications using Python. However, the test framework coming with Qt is focused
on C++, and only a subset of its functionality is available in Python. Together
with the "unittest" module in the Python standard library (which exposes a
heavyweight, xUnit-like API), this can make tests unnecessarily cumbersome to
write.

The pytest framework coupled with the pytest-qt plugin allows writing tests for
Qt/Python code in a much simpler way. It exposes the QTestLib API, but also adds
various high-level functionality with an API which is much more pythonic.

Examples of functionality provided by the pytest-qt plugin include:

- Waiting for Qt signals, conditions or callbacks
- Dealing with Qt logging and warning messages
- Automated testing of Qt models (QAbstractItemModel)
- QTestLib API for GUI testing
- Failing tests on exceptions in Qt virtual methods

This talk will give the audience a short introduction to pytest and explain how
to test Python/Qt code using the pytest-qt plugin. It will also take a quick
look at other useful pytest plugins which can be combined with pytest-qt.

Basic knowledge of Python and asynchronous GUI programming concepts is required.
Related Qt concepts will be explained briefly in the talk.

Duration: 30 minutes, including 5 minutes Q&A

### Reviewer notes

I've mainly given workshops so far (see my other submission), as well as smaller
talks which weren't recorded.

For an example of a talk that was recorded, see my talk about pytest at the
Swiss Python Summit 2016 (note that the video is rather old and I've done some
more speaking/workshops since then, but nothing I could find a recording of):
https://www.youtube.com/watch?v=rCBHkQ_LVIs
