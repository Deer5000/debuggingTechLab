# Debug Log

**Explain how you used the the techniques covered (Trace Forward, Trace Backward, Divide & Conquer) to uncover the bugs in each exercise. Be specific!**

In your explanations, you may want to answer:

- What is the expected vs. actual output?
- If there is a stack trace, what useful information does it contain?
- Which technique did you use, on which line numbers?
- What assumptions did you have about each line of code, and which ones were proven to be wrong?

_Example: I noticed that the program should show pizza orders once a new order is made, and that it wasn't showing any. So, I used the trace forward technique starting on line 13. I discovered the bug on line 27 was caused by a typo of 'pzza' instead of 'pizza'._

_Then I noticed another bug ..._

## Exercise 1

-  A few assumptions that im making are that both pages(Homepage & New Order) are working well and the issue occurs when people attempt to add pizza to the homepage.

- The first approach that I would take is to speak to a rubber ducky to find potential ways to fix this problem. I would also see if other items are being added correctly such as drinks, snacks, etc.

- Next I would use the divide and conquer technique to pinpoint where the bug is located(Probably in the "add pizza" section).

- I would then use the tracing forward technique to understand the code and if im unable to figure it out I would refer to a similar section of code(ex. adding drinks) and compare the two sections to see if I can find any similarities and/or differences that will help me solve this issue.

- I noticed there were multiple bugs in the app.py file and also the templte pages. A few of the variables were named diffrently which was causing the app to crash.

## Exercise 2

[[Your answer goes here!]]

## Exercise 3

[[Your answer goes here!]]
