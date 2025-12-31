# pytest - simple, rapid and fun testing with Python

- Tutorial (90 minutes)
- Topic: PyCon: Programming & Software Engineering & Testing
- Domain expertise: Novice
- Python expertise: Novice
- Supporting material: https://github.com/The-Compiler/pytest-basics
- Previous slides: https://bruhin.software/tmp/pytest-pyconde2025.pdf

## Abstract

The pytest tool offers a rapid and simple way to write tests for your Python code. This training gives an introduction with exercises to some distinguishing features, such as its assertions, marks and fixtures.

Despite its simplicity, pytest is incredibly flexible and configurable. We'll look at various configuration options as well as the plugin ecosystem around pytest.

## Description

# Preparation and Repository

See [The-Compiler/pytest-basics](https://github.com/The-Compiler/pytest-basics) on GitHub for exercise code and preparation steps. Please make sure you have at least a virtualenv with `pytest` (or the full `requirements.txt` in the repo) set up and the code cloned before the training starts, so that we don't lose any time with the boring setup parts.

See the README for detailed setup instructions.

# Schedule

- (25 minutes) **pytest feature walkthrough:**
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

- (5 minutes) **Where to go next:**
    * Useful CLI arguments to deal with failing tests
    * Overview of the plugin ecosystem around pytest


## Notes

My name (and pronouns) changed, but I'm still the same person :)

Regarding "already presented and recorded": Essentially this is the same tutorial [as at PyConDE 2025](https://www.youtube.com/watch?v=h3zlTirlwp4), but as always there are minor updates and improvements to the material from feedback gathered during my company trainings.
