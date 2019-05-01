# PyCon Balkan

## About

- Date: 3. - 5. October 2019
- Location: Hilton Belgrade, Serbia

## Timeline

- CfP open: 15. April 2019
- CfP closing: 15. July 2019

## Links

- [Website](https://pyconbalkan.com/)
- [CfP Infos](https://pyconbalkan.com/cfp)
- [CfP Submission](https://sessionize.com/pycon-balkan-2019/)

## Speaker info

- Previous talks: FIXME
- Speaker tagline: FIXME

### Speaker biography

FIXME

## Training
### Information

- Title: "**pytest - simple, rapid and fun testing with Python**"
- Length: 90-180 min
- Level: Intermediate
- Tags: Tools, Framework
- Session format: Workshop

### Description

*(WIP, mostly copy-pasted from EP 2016; 120-250 chars)*

The pytest tool presents a rapid and simple way to write tests for your Python code. This training gives a quick introduction with exercises into some distinguishing features. We’ll do exercises where we get existing non-pytest test suites to run with pytest and discuss migration strategies. We’ll finish with discussing topics and questions of participants related to their own test suites and usages.

**If you want to participate, please install pytest (e.g. in a virtualenv) before the training and download the [code examples](FIXME).**

This is the planned outline:

- (30 minutes) pytest feature walkthrough: automatic test discovery, assert statement, modular parametrizable fixtures, 150 plugins (FIXME)
- (60 minutes) pytest fixture mechanism: dependency injection, declaring and using function/module/session scoped fixtures, using fixtures from fixture functions, parametrizing fixtures. Exercises.
- (30 minutes): running nose/unittest/trial/Django suites with pytest. Discussing advantages and limitations. Exercise with a select existing real-life open source project.
- (30 minutes): Strategies for a) migrating to pytest b) using “autouse” fixtures in conjunction with XUnit-based setup/tearodwn methods. Exercise.
- (30 minutes): open space for questions and interactively solving pytest/unittest integration problems on real-life problems as time permits.

### Reviewer Notes

FIXME

## Talk
### Information

- Title: "**Testing PySide/PyQt code easily using the pytest framework**"
- Length: 30 minutes (25 minutes + 5 minutes Q/A)
- Level: Advanced
- Tags: Tools, Framework
- Session format: Talk

### Description

*(WIP, mostly copy-pasted from QtWS)*

Both PySide and PyQt allow rapid prototyping and development of Qt applications
using the Python programming language. However, the Qt Test framework is focused
on C++, and only a subset of its functionality is available in Python.
Together with the "unittest" module in the Python standard library (which exposes
a heavyweight, xUnit-like API), this can make tests unnecessarily cumbersome to
write.

The pytest framework coupled with the pytest-qt plugin allows writing tests for
Qt/Python code in a much more straightforward and fun way. It exposes the
QTestLib API, but also adds various high-level functionality with an API which
is more suitable for Python code.

This talk will give the audience a short introduction to pytest and explain how
to test Python/Qt code using the pytest-qt plugin. It will also take a quick
look at other useful pytest plugins which can be combined with pytest-qt.

### Reviewer notes

FIXME
