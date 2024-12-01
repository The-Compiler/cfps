# pytest tips and tricks for a better testsuite

## Abstract

pytest lets you write simple tests fast - but also scales to very complex scenarios: Beyond the basics of no-boilerplate test functions, this training will show various intermediate/advanced features, as well as gems and tricks.

To attend this training, you should already be familiar with the pytest basics (e.g. writing test functions, parametrize, or what a fixture is) and want to learn how to take the next step to improve your test suites.

If you're already familiar with things like fixture caching scopes, autouse, or using the built-in `tmp_path`/`monkeypatch`/... fixtures: There will probably be some slides about concepts you already know, but there are also various little hidden tricks and gems I'll be showing.

## Description

We'll cover things like:

- Recommended pytest settings for more strictness
- What's xfail and why is it useful?
- How to mark an entire test file or single parameters
- Ways to deal with parametrize IDs and syntax
- Useful built-in pytest fixtures
- Caching for fixtures
- Using fixtures implicitly
- Advanced fixture and parametrization topics
- How to customize fixtures behavior based on markers or custom CLI arguments
- Basics of patching, mocking, and alternatives
- Short intro to property-based testing with Hypothesis
- Various useful plugins, and a short teaser about how to write your own

## Notes

I'd prefer a 3h slot (like at PyConDE 2022), but I can make it work in 1.5h if needed (mainly more live demos, less exercises; also cutting out some sneak peeks at intermediate topics like plugins or hypothesis).

## Prerequisites

A supported Python + pytest version. See https://github.com/The-Compiler/pytest-tips-and-tricks/tree/pyconde2025 for details.

## Reviewer notes

- I'd prefer a training focused on basics (my other proposal), as the last time I've done that at a conference was at PyConDE 2022. I've since done major improvements to the materials.
- This proposal will be quite close to what I've shown at EP 2022/2023 and PyConDE 2024, but with everything I've improved and refined since then.
- Thus, I'm unsure about the "was already presented and recorded" question. I've made countless updates (~12 company trainings since PyConDE 2024, which contain this material and I improve things after each training). However, there wasn't a big major update.
- The prerequisites link is not up yet, but will be similar to https://github.com/The-Compiler/pytest-tips-and-tricks/tree/pyconde2024


# pytest - simple, rapid and fun testing with Python

## Abstract

The pytest tool offers a rapid and simple way to write tests for your Python code. This training gives an introduction with exercises to some distinguishing features, such as its assertions, marks and fixtures.

Despite its simplicity, pytest is incredibly flexible and configurable. We'll look at various configuration options as well as the plugin ecosystem around pytest.

## Description

- (20 minutes) **pytest feature walkthrough:**
    * Automatic test discovery
    * Assertions without boilerplate via the assert statement
    * Configuration and commandline options
    * Marking and skipping tests
    * Data-driven tests via parametrization
    * Exercises

- (60 minutes) **pytest fixture mechanism:**
    * Setup and teardown via dependency injection
    * Declaring and using function/module/session scoped fixtures
    * Using fixtures from fixture functions
    * Parametrizing fixtures
    * Looking at useful built-in fixtures (managing temporary files, patching, output capturing)
    * Exercises

- (10 minutes) **Where to go next:**
    * Useful CLI arguments to deal with failing tests
    * Overview of the plugin ecosystem around pytest

## Notes

I'd prefer a 3h slot (like at PyConDE 2022), but I can make it work in 1.5h if needed (mainly more live demos, less exercises; also cutting out some sneak peeks at intermediate topics like plugins or hypothesis).

## Reviewer notes

- I'd prefer this to a intermediate/advanced training (my other proposal), as the last time I've done this format at a conference was at PyConDE 2022. I've since done major improvements to the materials (thus, not checking "presented and recorded before").
- I don't have a GitHub repository for this format yet, but plan to set up something similar to https://github.com/The-Compiler/pytest-tips-and-tricks/tree/pyconde2024


# Bio

Florian Bruhin ("The Compiler") is a long-time contributor and maintainer of both the pytest framework and various plugins. He discovered pytest in 2015 —  since then, he has given talks and conducted workshops about pytest at various conferences and companies. His primary project, qutebrowser (a keyboard-focused web browser), has grown from a hobby to a donation-funded part-time job.
