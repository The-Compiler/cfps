# Property based testing with Hypothesis

- Type: Talk (30 minutes)
- Topic: PyCon: Programming & Software Engineering & Testing
- Domain expertise: Novice
- Python expertise: Intermediate
- Supporting material: https://github.com/The-Compiler/hypothesis-talk
- Previous slides: https://bruhin.software/tmp/hypothesis-sps24.pdf

## Abstract

The [website](https://hypothesis.works) of the Hypothesis project used to boldly assert: *"Normal 'automated' software testing is surprisingly manual. Every scenario the computer runs, someone had to write by hand. Hypothesis can fix this."*

While it's debatable whether property-based testing should fully replace the manual parametrization of tests with different inputs and outputs, there's no doubt that Hypothesis is a powerful tool for uncovering bugs nobody would even have considered looking for. In fact, during its development, the authors of Hypothesis accidentally discovered countless bugs in CPython and libraries, thus coining the term *"The Curse of Hypothesis"*.

The framework, although incredibly powerful, might seem overwhelming at first. In this talk, I will demonstrate how even simply throwing random strings at functions can reveal surprising bugs. From there, we'll progress towards generating more complex data, which will be less daunting than it initially appears. You'll also see how Hypothesis seamlessly integrates with various ecosystems and can be a valuable tool in any developer's toolkit.

## Description

The talk will show Hypothesis based on two small projects:

# RPN Calculator

- Introduction to the example project (with bugs, it will fit on one slide!)
- Introduction to Hypothesis
- Hypothesis finding an obvious bug
- Hypothesis then finding a bug that I never would have thought of

# Run Length Encoding

- Implementing RLE in Python
- Hypothesis finding a bug
- Introducing a more subtle bug and letting Hypothesis find it

# ...and more

- How Hypothesis found bugs in my professor's code when writing a compiler at university (and helped me in getting the best possible grade)
- More possibilities of what Hypothesis can do

## Notes

My name (and pronouns) changed, but I'm still the same person :)

If I need to choose, I would prefer giving one of my two tutorials rather than giving the talk.

Regarding "already presented and recorded": Given at [Swiss Python Summit 2024](https://media.ccc.de/v/sps24-56254-property-based-testing-with) as a short-notice replacement for a cancelled speaker, but never given with improved/refined material.
