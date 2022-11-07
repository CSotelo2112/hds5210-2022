# Notes on the Midterm

* _Correctness    (out of 40):_ 40
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 10

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Nice comments in your docstrings and use of tests throughout.

## Step 1
* Because there's only one `payments` in the `allowed_amounts` this works fine. However, if there were cases of multiple items, your code would only add in the last one, based on the placement of your `amounts_total += values` code.

## Step 2
* Nice work.
* A little confusing with your identify the allowed_amount as `values` and then set `output=values` in a separate line.  I don't see the value in that.

## Step 3
* Rather than repeating everything again from `get_rate()`, you should ahve just called `get_rate()`.  I deducted 1 point from _Good Practices_ for this.

## Step 4
* Nice work. Easy to follow.