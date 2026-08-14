---
title: Home
layout: home
nav_order: 1
---

# {{ site.title }}
{: .no_toc }

{{ site.description }}.
{: .fs-6 .fw-300 }


This [Learning Hour] is about **test lists**: writing down the cases you intend to cover *before* you write a
single test, so a pair or ensemble can clarify the problem and agree on scope together.

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

## Learning Goals 🎯

- Understand what a test list is and why writing one before coding helps clarify the problem
- Know the checklist for a well-formed test list item (clear input/output, an explicit rule, easy to turn into code)
- Practice writing and revising a test list on a real kata, and cross-check it against the checklist

## Connect activity to get everyone thinking about the topic (⏱️ 10 min)

**Warm-up.** You're about to write code. Which of these best matches you?

- Start with a test straight away, and look back at the requirements as you go
- Read the requirements first, list out the test cases you can think of, then start
- Sketch the solution with a colleague first, then pick a couple of simple tests
- Write the code first, and add tests afterwards to describe what it does

See [Connect Activities] in the [Samman Coaching] website for more ideas on how to connect with your team and
introduce the topic of this Learning Hour.

## An explanation of a new Concept or a coding demo (⏱️ 15 min)

**Why write a test list?** It clarifies the problem, groups and categorizes cases, surfaces edge cases, gives you
clear names for test classes and methods up front, doubles as a completion criterion for TDD, and builds shared
understanding when pairing or ensembling.

**Test lists + AI agents.** The same reasoning applies, even more so, when an AI coding agent is doing the typing.
A one-shot prompt hides which cases the agent actually covered — a wrong assumption early on quietly corrupts
everything built on top of it. Writing the test list first means scope is agreed *before* code exists, and feeding
the agent one item at a time gives you a checkpoint after each one, so a wrong turn gets caught early rather than
after the whole thing is built. See [Claude Code Best Practices] and [Coding assistants do not replace pair
programming] for more on why an incremental, reviewed workflow beats letting an agent run ahead unsupervised.

See [Concept Explanation] for the full checklist and a worked example (prime numbers), and the
[Concept Activities] in the [Samman Coaching] website for more ideas on how to introduce a new Concept or do a
coding demo.

## Concrete Practice in a coding exercise (⏱️ 45 min)

- Write a test list for Fizzbuzz
- If you still have time, do the same for relative path normalization
- Before moving to the next exercise, cross-check your list against the checklist in [Concept Explanation]

**Facilitator notes.** Fizzbuzz's rules are stated explicitly in the prompt, so groups tend to move through it
quickly. Relative path normalization is deliberately harder: the prompt only says a path "may contain `.` and
`..` with the usual meanings," so groups have to work out the actual rules from examples before a test list makes
sense — that reverse-engineering is where the richest conversation happens, so let it run rather than jumping in
with the rules. Expect groups to raise open questions they can't fully resolve in the time box — negative numbers,
non-integer input, empty or invalid paths, trailing separators. Treat these as good signal, not gaps to close:
the point is to capture them as explicit assumptions on the list, not to enumerate every case.

See [Concrete Practice Activities] in the [Samman Coaching] website for more ideas on how to design a coding
exercise to practice the new Concept.

## Conclusions discussion and reflection (⏱️ 20 min)

- Was writing the test list easier or harder than you expected?
- Did you rework the list — did writing a later item change how you saw an earlier one?
- Remember: a test list is a conjecture, not a full spec — the code is the proof
- When should you use test lists?
- How does it feel when we use test lists?

**Themes to listen for:** building the list together surfaces real conversation and shared understanding, often
before any code is written; understanding the problem matters more than front-loading every input; it's fine to
start from concrete examples and only generalize into a rule afterwards; lists get reworked as understanding
deepens, and that reworking is the exercise working as intended, not a false start; a clear input/output/rule
shape per item was consistently called out as the most useful habit to keep.

See [Conclusions Activities] in the [Samman Coaching] website for more ideas on how to facilitate a discussion to
reflect on the learning experience and draw conclusions.

## References

- [Learning Hour] — the Samman format this session follows
- [Concept Explanation] — the full checklist and worked example
- [A facilitated run of this Learning Hour](https://miro.com/app/board/uXjVHVVo_9g=/?moveToWidget=3458764654164264768) — real teams' completed test lists and take-aways, on Miro
- [Samman Coaching] — [Connect Activities] · [Concept Activities] · [Concrete Practice Activities] · [Conclusions Activities]


[Learning Hour]: https://sammancoaching.org/reference/learning_hour_definition.html
[Concept Explanation]: explanation/concept-explanation.html
[Connect Activities]: https://sammancoaching.org/activities/connect.html
[Concept Activities]: https://sammancoaching.org/activities/concept.html
[Concrete Practice Activities]: https://sammancoaching.org/activities/concrete.html
[Conclusions Activities]: https://sammancoaching.org/activities/conclusions.html
[Samman Coaching]: https://sammancoaching.org/
[Claude Code Best Practices]: https://code.claude.com/docs/en/best-practices
[Coding assistants do not replace pair programming]: https://martinfowler.com/articles/exploring-gen-ai/05-not-your-pair-programmer.html



