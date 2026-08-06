# Problem Solving Submission

This file must be written by the student in their own words.

Use this template only for OJ problems that are marked as learning-log required.

Do not ask AI to write this file for you. AI may help check grammar, formatting, or clarity after you have written your own content.

If AI was used for this learning-log-required problem, also complete `ai_reflection.md`.

---

## 1. OJ Information

OJ problem number/title:

```text
3024/SurprisingVote
```

OJ submission ID, if submitted:

```text
588882
```

OJ status:

```text
Pass
```

Independent time spent on this problem:

```text
1-3 hours
```

Choose one:

```text
0-15 minutes
15-30 minutes
30-60 minutes
1-3 hours
3-6 hours
6-24 hours
1-3 days
4-7 days
1-4 weeks
More than 4 weeks
```

How to count this time:

- Count only the time you actively worked on this problem independently.
- Start counting from when you first read the problem.
- Do not include breaks, meals, classes, sleep, time spent on other problems, or time when you were not working on this problem.
- If you used AI, count only the independent time before your first AI prompt.
- If you asked a friend, TA, or instructor for help, count only the independent time before your first help request.
- If you used both AI and human help, count only the independent time before the first outside help of any kind.
- If you did not use AI or human help, count the time before writing this `submission.md`.
- An estimate is acceptable, but it must be honest.

---

## 2. My Understanding

Write the problem in your own words.

Also explain the input, output, and important constraints.

If you do not fully understand the problem yet, write what you currently understand. Your understanding may be incomplete or incorrect, but you must make a genuine attempt.

```text
the problem required you to write a code that determine whether the score is surprising or not based on 2 inputs by way of whether it is possible that the difference between the highest and lowest is above 2
the inputs are the total score and the max score
the outputs are "Surprising" or "Not Surprising" based on whether it is possible that the difference between the highest score and lowest score is above 2 or not
```

--

## 3. My First Plan

Write your first plan before getting help from AI, a friend, a TA, an instructor, or before finalizing your code.

If you used AI, write the plan you had before your first AI prompt.

If you asked a friend, TA, or instructor for help, write the plan you had before asking for help.

If you did not use AI or human help, write the plan you had before or while you started coding.

This can be rough. It may be incomplete or different from your final solution.

You may write pseudocode, a flowchart idea, or step-by-step thinking.

```text
Step 1: write code that accepts 2 inputs: total score and max score
Step 2: write code that calculates the lowest score
Step 3: write code that checks if the difference between highest and lowest score is more than 2
Step 4: write code that print surprising if the difference between highest and lowest score is more than 2, and print not surprising if it isn't
```

---

## 4. My Final Approach

Briefly explain the final algorithm or method you actually used in your submitted code.

This section is different from Section 3:

- Section 3 is your first plan before AI, human help, or before the final code.
- Section 4 is the final method used in your actual solution.
- If your final approach is the same as your first plan, write that it is the same and briefly explain why.

Do not copy AI's explanation.

Do not copy another person's explanation.

```text
the final code is very different from the first plan, basically a different plan. the final code checks if the highest score is less than or equals to 2 and immediately print not surprising if it is instead of checking it later
then if the highest score is more than 2, there's two nested if else statements, one that calculates lowest score, and another that calculates the difference between the highest score and lowest score and check if it is more or less than 2
and if the difference between the highest and lowest score is more than 2, then print surprising
```

---

## 5. My Tests

Write at least 3 test cases that you tried or designed by yourself.

Try to choose test cases that are different from each other.

For each test case, explain why you chose it.

If the input or output has many lines, write them inside the text blocks.

### Test Case 1

Why I chose this case:

```text
to test the sample testcase to check whether the code is working as intended by the problem
```

Input:

```text
20
8
```

Expected output:

```text
Surprising
```

Actual output:

```text
Surprising
```

Result:

```text
Pass
```

### Test Case 2

Why I chose this case:

```text
to test another sample testcase to check whether the code is working as intended by the problem
```

Input:

```text
29
10
```

Expected output:

```text
Not Surprising
```

Actual output:

```text
Not Surprising
```

Result:

```text
Pass
```

### Test Case 3

Why I chose this case:

```text
to test random inputs
```

Input:

```text
125
93
```

Expected output:

```text
should be Surprising
```

Actual output:

```text
Surprising
```

Result:

```text
Pass
```

---

## 6. AI Use

Did you use AI for this problem?

```text
No
```

If yes, also complete:

```text
ai_reflection.md
```

If you only asked a friend, TA, or instructor and did not use AI, you do not need to complete `ai_reflection.md`.

---

## 7. Human Help / Collaboration

Did you ask a friend, TA, instructor, or another person for help on this problem?

```text
Yes
```

If yes, briefly explain what kind of help you received.

Allowed examples:

- explanation of the problem statement
- explanation of a programming concept
- hint about the approach
- debugging discussion
- test-case discussion
- help understanding an error message

Not allowed:

- copying another person's code
- submitting another person's solution
- asking another person to write the solution for you
- using another person's OJ submission
- asking another person to submit to the OJ for you

Who helped you?

```text
a friend
```

What did they help with?

```text
they helped me understand the problem much, much better
they also gave hints, and helped with a lot of debugging
```

What did you still do by yourself?

```text
writing the code, understanding the problem explanation, researching programming concepts(they ended up unused), and reading the error message and fixing the code until it worked
```

Did you copy any code from another person?

```text
No
```

---

## 8. Student Declaration

Write `Yes` for each statement.

| Statement | Yes/No |
|---|---|
| I wrote this submission in my own words. |Yes|
| I understand my final code. |Yes|
| I recorded the real OJ status. |Yes|
| I did not copy AI-generated text directly into this file. |Yes|
| I did not copy code from another person. |Yes|
| If I received human help, I disclosed it in this file. |Yes|
| I submitted the final code to the OJ by myself. |Yes|
