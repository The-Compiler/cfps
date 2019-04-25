# Europython 2019

## About

- Date: 8. - 14. July 2019
- Location: Basel
- "Room capacity for the trainings rooms is approx. 100 seats."

## Timeline

- CfP open: 25. April 2019
- CfP closing: 12. May 2019

## Links

- [Website](https://ep2019.europython.eu/)
- [FAQ](https://ep2019.europython.eu/faq)
- [CfP Infos](https://ep2019.europython.eu/events/call-for-proposals/)
- [CfP blogpost](https://www.europython-society.org/post/184430536360/europython-2019-call-for-proposals)
- [CfP Submission](https://ep2019.europython.eu/cfp/submit-proposal/)
- [2016 training submission](https://ep2016.europython.eu/conference/talks/pytest-simple-rapid-and-fun-testing-with-python-1)

## Training
### Information

- Title: "**pytest - simple, rapid and fun testing with Python**" *(max 80 chars)*
- Subtitle: FIXME *(max 100 chars)*
- Length: 3h
- Python skill level: FIXME *(Beginner/Intermediate/Advanced)*
- Domain Expertise: FIXME *(The domain expertise your audience should have to follow along (e.g. how much should one know about DevOps or Data Science already) - Beginner/Intermediate/Advanced)*
- Tags: Test Libraries, TDD, Best Practice, Testing, FIXME *(max. 5)*

### Abstract (longer version)

*(WIP, mostly copy-pasted from 2016)*

*Suggested size: 1500 chars. Description of the session proposal you are submitting. Be sure to include the goals and any prerequisite required to fully understand it. See the section Submitting Your Talk, Trainings, Helpdesk or Poster of the CFP for further details.*

The pytest tool presents a rapid and simple way to write tests for your Python code. This training gives a quick introduction with exercises into some distinguishing features. We’ll do exercises where we get existing non-pytest test suites to run with pytest and discuss migration strategies. We’ll finish with discussing topics and questions of participants related to their own test suites and usages.

**If you want to participate, please install pytest (e.g. in a virtualenv) before the training and download the [code examples](FIXME).**

This is the planned outline:

- (30 minutes) pytest feature walkthrough: automatic test discovery, assert statement, modular parametrizable fixtures, 150 plugins (FIXME)
- (60 minutes) pytest fixture mechanism: dependency injection, declaring and using function/module/session scoped fixtures, using fixtures from fixture functions, parametrizing fixtures. Exercises.
- (30 minutes): running nose/unittest/trial/Django suites with pytest. Discussing advantages and limitations. Exercise with a select existing real-life open source project.
- (30 minutes): Strategies for a) migrating to pytest b) using “autouse” fixtures in conjunction with XUnit-based setup/tearodwn methods. Exercise.
- (30 minutes): open space for questions and interactively solving pytest/unittest integration problems on real-life problems as time permits.

### Abstract (short version)

*Suggested size: < 500 chars*

FIXME

### Prerequisites

*What should attendees be familiar with already, important for intermediate and advanced talks. E.g. data visualization basics, data analysis*

FIXME

### Additional information for talk reviewers

*Please add anything you may find useful for the review of your session proposal, e.g. references of where you have held talks, blogs, YouTube channels, books you have written, etc. This information will only be shown for talk review purposes.*

FIXME

## Talk
### Information

- Title: "**Testing PySide/PyQt code easily using the pytest framework**" *(max 80 chars)*
- Subtitle: FIXME *(max 100 chars)*
- Length: 30 minutes (25 minutes + 5 minutes Q/A)
- Python skill level: FIXME *(Beginner/Intermediate/Advanced)*
- Domain Expertise: FIXME *(The domain expertise your audience should have to follow along (e.g. how much should one know about DevOps or Data Science already) - Beginner/Intermediate/Advanced)*
- Tags: Test Libraries, TDD, Best Practice, Testing, PyQt, FIXME *(max. 5)*

### Abstract (longer version)

*(WIP, mostly copy-pasted from QtWS)*

*Suggested size: 1500 chars. Description of the session proposal you are submitting. Be sure to include the goals and any prerequisite required to fully understand it. See the section Submitting Your Talk, Trainings, Helpdesk or Poster of the CFP for further details.*

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

### Abstract (short version)

*Suggested size: < 500 chars*

FIXME

### Prerequisites

*What should attendees be familiar with already, important for intermediate and advanced talks. E.g. data visualization basics, data analysis*

FIXME

### Additional information for talk reviewers

*Please add anything you may find useful for the review of your session proposal, e.g. references of where you have held talks, blogs, YouTube channels, books you have written, etc. This information will only be shown for talk review purposes.*

FIXME
