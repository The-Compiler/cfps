# Europython 2019

## About

- Date: 8. - 14. July 2019 (Mon/Tue trainings, Wed-Fri conference)
- Location: Basel
- "Room capacity for the trainings rooms is approx. 100 seats."
- "In case you have already purchased a ticket for the conference before knowing whether you have been accepted as a speaker or for a training, and thus cannot use the discount coupon, we will be refunding the corresponding amount after the conference **upon request**."
- "EuroPython does community based talk voting"

## Timeline

- CfP open: 25. April 2019
- CfP closing: 12. May 2019
- "Refund coupons which are not used and speaker refunds for already bought tickets which are not requested until one week after the conference (July 21), will be put to good use and automatically go into the financial aid budget for next year's conference."

## Links

- [Website](https://ep2019.europython.eu/)
- [FAQ](https://ep2019.europython.eu/faq)
- [CfP Infos](https://ep2019.europython.eu/events/call-for-proposals/)
- [CfP blogpost](https://www.europython-society.org/post/184430536360/europython-2019-call-for-proposals)
- [CfP Submission](https://ep2019.europython.eu/cfp/submit-proposal/)
- [2016 training submission](https://ep2016.europython.eu/conference/talks/pytest-simple-rapid-and-fun-testing-with-python-1)

## Training
### Information

- Title: "**Introduction to pytest**" *(max 80 chars)*
- Subtitle: Simple, rapid and fun testing with Python
- Length: 3h
- Python skill level: Intermediate
- Domain Expertise: Beginner
- Tags: Test Libraries, TDD, Best Practice, Testing *(max. 5)*

### Abstract (longer version)

*Suggested size: 1500 chars. Description of the session proposal you are
submitting. Be sure to include the goals and any prerequisite required to fully
understand it. See the section Submitting Your Talk, Trainings, Helpdesk or
Poster of the CFP for further details.*

The pytest tool presents a rapid and simple way to write tests for your Python
code. This training gives a quick introduction with exercises into some
distinguishing features. We'll do exercises where we get existing non-pytest
test suites to run with pytest and discuss migration strategies. We'll finish
with discussing topics and questions of participants related to their own test
suites and usages.

This is the planned outline:

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
- (30 minutes): Running existing nose/unittest/trial/Django suites with pytest:
  * Discussing advantages and limitations
  * Strategies for migrating to pytest
  * Using "autouse" fixtures in conjunction with XUnit-based setup/teardown methods
  * Exercises
- (30 minutes): Useful third-party plugins:
  * Coverage integration
  * Property-based testing (automated testcase generation) via Hypothesis.
- (30 minutes): Open space for questions:
  * Interactively solving pytest integration problems on real-life projects as time permits.
  
Note that the structure of the workshop is similar to the ones I've given at
Europython 2015 and 2016 in Bilbao.

### Abstract (short version)

*Suggested size: < 500 chars. Be sure to include relevant info in both the short
and long abstract when submitting your proposal as attendees will not see the
short abstract when voting!*

The pytest tool presents a rapid and simple way to write tests for your Python
code. This training gives a quick introduction with exercises into some
distinguishing features. We'll do exercises where we get existing non-pytest
test suites to run with pytest and discuss migration strategies. We'll finish
with discussing topics and questions of participants related to their own test
suites and usages.

### Prerequisites

*What should attendees be familiar with already, important for intermediate and
advanced talks. E.g. data visualization basics, data analysis*

Basic Python OOP knowledge (e.g. what a class/instance is) is required. Knowing
what an assertion or a decorator are is a bonus, but will also be explained
during the workshop.

### Additional information for talk reviewers

*Please add anything you may find useful for the review of your session
proposal, e.g. references of where you have held talks, blogs, YouTube channels,
books you have written, etc. This information will only be shown for talk review
purposes.*

I've given similar workshops at Europython 2015 and 2016. They were visited by
many attendees and I've received good feedback. Additionally, I've conducted
longer (3-day) workshops about pytest/tox/devpi in various companies, see e.g.:
https://www.python-academy.com/courses/specialtopics/python_course_testing.html

Those workshops weren't recorded, and I haven't given many talks yet - for an
example, see my talk at the Swiss Python Summit 2016:
https://www.youtube.com/watch?v=rCBHkQ_LVIs

## Talk
### Information

- Title: "**Testing PySide/PyQt code easily using the pytest framework**" *(max 80 chars)*
- Subtitle: **How to use pytest and pytest-qt, and how it's better than unittest and QtTest** *(max 100 chars)*
- Length: 30 minutes (25 minutes + 5 minutes Q/A)
- Python skill level: Intermediate *(Beginner/Intermediate/Advanced)*
- Domain Expertise: Intermediate *(The domain expertise your audience should have to follow along (e.g. how much should one know about DevOps or Data Science already) - Beginner/Intermediate/Advanced)*
- Tags: Test Libraries, TDD, Best Practice, Testing, PyQt *(max. 5)*

### Abstract (longer version)

*Suggested size: 1500 chars. Description of the session proposal you are submitting. Be sure to include the goals and any prerequisite required to fully understand it. See the section Submitting Your Talk, Trainings, Helpdesk or Poster of the CFP for further details.*

Both PySide and PyQt allow rapid prototyping and development of Qt GUI applications
using Python. However, the test framework coming with Qt is focused on C++, and
only a subset of its functionality is available in Python. Together with the
"unittest" module in the Python standard library (which exposes a heavyweight,
xUnit-like API), this can make tests unnecessarily cumbersome to write.

The pytest framework coupled with the pytest-qt plugin allows writing tests for
Qt/Python code in a much more straightforward and fun way. It exposes the
QTestLib API, but also adds various high-level functionality with an API which
is much more pythonic.

Examples of functionality provided by the pytest-qt plugin include:

- Waiting for Qt signals, conditions or callbacks
- Dealing with Qt logging and warning messages
- Automated testing of Qt models (QAbstractItemModel)
- QTestLib API for GUI testing
- Failing tests on exceptions in Qt virtual methods

This talk will give the audience a short introduction to pytest and explain how
to test Python/Qt code using the pytest-qt plugin. It will also take a quick
look at other useful pytest plugins which can be combined with pytest-qt.

### Abstract (short version)

*Suggested size: < 500 chars*

PySide and PyQt allow development of Qt GUI applications using Python. However,
writing tests using Python's unittest and Qt's test API can be unnecessarily
cumbersome.

The pytest framework coupled with the pytest-qt plugin allows writing tests for
Qt/Python code in a much more straightforward and fun way. It does so by adding
various high-level functionality useful for testing Qt code.

This talk will give the audience an introduction to pytest, the pytest-qt
plugin and other related plugins.

### Prerequisites

*What should attendees be familiar with already, important for intermediate and advanced talks. E.g. data visualization basics, data analysis*

Basic knowledge of Python and asynchronous GUI programming concepts is required. Related Qt concepts (signals/slots) will be explained quickly in the talk.

### Additional information for talk reviewers

*Please add anything you may find useful for the review of your session proposal, e.g. references of where you have held talks, blogs, YouTube channels, books you have written, etc. This information will only be shown for talk review purposes.*

I've mainly given workshops so far (see my other submission), as well as smaller
talks which weren't recorded.

For an example of a talk which was recorded, see my talk about pytest at the
Swiss Python Summit 2016:
https://www.youtube.com/watch?v=rCBHkQ_LVIs
