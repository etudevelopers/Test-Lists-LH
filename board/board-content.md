# Test Lists — Learning Hour: Board Content

Verbatim transcription of the Miro board [Test Lists – Learning hour](https://miro.com/app/board/uXjVH07M1TQ=/), captured via the Miro MCP tools (`board_list_items`).

## Slide deck

### 1. Title

**Test lists**
**Learning hour**

### 2. Warm up

**Warm up**

You are about to write some code. What do you do first? Read through these descriptions and choose the one that best matches how you would behave.

- Start by opening a new file in a code editor. Begin declaring a test case. Refer back to the requirements document and pick the first thing it refers to to turn into a test. Go back to the editor and write that test case.
- Start by reading the requirements carefully. Every time you find something that will need a test case, highlight it. Analyze each highlighted case and identifying edge cases, invariants etc. When you're ready, go to a code editor and declare a test case for each thing you highlighted. Comment out all but the first test case.
- Start by reading the requirements carefully and sketching ideas together with a colleague. When you have understood more about what's needed, note down some test cases you'll need. Analyze the list and pick the simplest, smallest one to begin with. Open your code editor and write that test.
- Start by reading the requirements carefully. When you've understood them, write code to fulfill the requirements. When you think everything is working, write a test case that checks the code works. Continue adding test cases one by one checking each passes as you finish it.

Source: <https://sammancoaching.org/exercises/warm_up_questions/tdd_overview_what_would_you_do.html>

*(A decorative grid of 15 emoji avatars sits at the top of this slide, presumably for participants to pick as their identifier.)*

### 3. Why write a test list?

**Why write a test list?**

1. Clarify the problem.
2. Group/categorize different cases.
3. Recognize important edge cases.
4. Gives clear names to test classes and methods.
5. When doing TDD: know when you are done.
6. When pairing/ensembling: shared understanding.

### 4. Checklist

**Checklist**

1. Each item has a **clear before/after or input/output**.
2. Each item has a motivation or **associated rule** or rules, **in plain language**.
3. Each item can **easily be translated** into code.
4. Not a full spec, only enough to span the fundamentals.
   - (The list is a conjecture, the code is the proof.)

### 5. Test lists + AI agents

**Test lists + AI agents**

1. One-shot prompt: you can't see which cases the agent covered — a wrong assumption on item 2 quietly corrupts everything built after it.
2. Test list first: scope gets agreed *before* code exists — you're reviewing a plan, not reverse-engineering a diff.
3. One item at a time: a checkpoint after each item — catch a wrong turn at item 2, not after the whole thing is built.
4. Same rule as before: the list is a conjecture — now the agent supplies the proof, but only for the conjecture you actually approved.

Sources:

- <https://code.claude.com/docs/en/best-practices>
- <https://martinfowler.com/articles/exploring-gen-ai/05-not-your-pair-programmer.html>

### 6. Example

**Example**

**A prime number is a natural number with exactly two distinct, positive divisors.**

1. One is not a prime number: only *one distinct* divisor (itself)
2. Two is a prime number: 1 & 2 as positive divisors
3. Four is not a prime number: *more than two* divisors (1, 2, & 4)
4. Zero is not a prime number: not a *natural number* (edge case)

Easy to generate new examples.

### 7. Practice

**Practice**

1. Write a test list for Fizzbuzz
2. If you still have time, start on relative path normalization
3. Before moving to the next exercise, check your list against the "Checklist"

### 8. Wrap up

**Wrap up**

1. Was it easier/harder than you thought?
2. Did you rework the list or change earlier items after writing down later items?
3. Remind yourself what to look for in a test list.

### 9. Your take-aways

**Your take-aways**

*(Empty sticky note area for participant responses — no content captured.)*

## Team workspace frames

Four identical 4:3 frames, each for a pair/trio of participants (frame titles: "Team member 1, Team member 2" ×3, "Team member 1, Team member 3" ×1). Each frame contains:

**1 - Fizzbuzz**

Write a test list for a program that takes an integer as an argument and prints the number to stdout. However, if the number is a multiple of three, the program should print "Fizz" instead of the number and if it's a multiple of five it should print "Buzz". If the number is a multiple of both three and five, it should print "Fizzbuzz".

*(Yellow sticky note beside this exercise — empty.)*

**2 - Relative path normalization**

Write a test list for a function that takes a relative path as a string and returns its normalized equivalent. A path may contain "." and ".." with the usual meanings.

*(Pink sticky note beside this exercise — empty. Each frame also has an image placeholder, likely a team photo/avatar.)*

## Notes

- All sticky notes across the board were empty at the time of capture — the session's participant output was not recorded on the board.
- The board follows the Samman Technical Coaching learning-hour format: warm-up → concept introduction → worked example → practice → reflection → take-aways.
