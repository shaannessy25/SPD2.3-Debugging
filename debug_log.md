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
I first tried to run the app.py file and found I had an environment error. I then installed the 2 packages flask and flask sqlalchemy. I then ran the flask server and
tested the website. I found a TypeError for the variable topping. I then checked to see what line the issue was arising
    Fixes:
        -changed line 71 to getList
        -Onsumbit redirects to home line 90
        -fullfill order was changed to a get request

## Exercise 2
I first needed to setup my environment by installing python-env. Once I was able to run it, I tested the program and noticed I had an internal server error.
I then checked my terminal to see a traceback error on line 52. I noticed that the context variables were not matching the city and units variables in the results method
    Fixes: 
        -line 39 changed to 'city' from 'users_city'
        -line 40 changed 'units' from 'requested_units'

## Exercise 3
* Changed right_side[i] to right_side[j]
* Updated binary search by getting whole number instead of float when dividing
