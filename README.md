# HW 1: ChatGPT vs. Wikipedia
**Due: September 28, 9:00 AM**

For this assignment, please complete the _problem set_ found in `hw1-pset.ipynb`. The problem set includes coding problems as well as written problems.

For the coding problems, you will implement functions defined in the Python file `hw1.py`, replacing the existing code (which raises a `NotImplementedError`) with your own code. **Please write all code within the relevant function definitions**; failure to do this may break the rest of your code.

For the written problems, please submit your answers in PDF format, using the filename `hw1-written.pdf`. Make sure to clearly mark each problem in order to minimize the chances of grading errors.

You do not need to submit anything for Problem 2f.

You are free to use any resources to help you with this assignment, including books, websites, or AI assistants such as ChatGPT (as long as such assistants are fully text-based). You are also free to collaborate with any other student or students in this class. However, you must write and submit your own answers to the problems, and merely copying another student's answer will be considered cheating on the part of both students. If you choose to collaborate, please list your collaborators at the top of your `hw1-written.pdf` file. If you choose to use ChatGPT or a similar AI assistant to help you with this assignment in any way, please include a file called `hw1-chatgpt-logs.txt` with a full transcript of all prompts and responses used for this assignment. Your use of AI assistants cannot involve generating images or any other content that cannot be included in a `.txt` file.

## Setup

You will need to complete your code problems in Python 3, preferably Python 3.8 or later. Apart from the standard Python libraries, the only dependency required for this assignment is [NLTK](https://www.nltk.org/). The problem set itself is a Jupyter notebook; it is highly recommended that you are able to run notebooks on your own computer in order to complete this assignment.

For this assignment, you will be working with the ChatGPT vs. Wikipedia corpus that we have been discussing in class. Please [download the corpus from Sophie's Google Drive](https://drive.google.com/file/d/1qH9bj9yWJGsqXRtUUpvwGhMsi_x1Z7nB/view) and make sure that it is saved to the same folder where your `hw1.py` and `hw1-pset.ipynb` files are located.

## Submission

For your submission, please upload the following files to [Gradescope](https://www.gradescope.com):
* `hw1.py`
* `hw1-written.pdf`
* `hw1-chatgpt-logs.txt` (if you used ChatGPT or a similar text-based AI assistant)

Do not change the names of these files, and do not upload any other files to Gradescope. Failure to follow the submission instructions may result in a penalty of up to 1 point.

## Grading

The point values for each problem are given below. Problem 1h is worth 1 extra credit point, but the maximum possible grade on this assignment is 20 points. If you earn a total of 20 points or more _including the extra credit points_, then your grade will be 20.

| Problem                                         | Problem Type     | Points |
|-------------------------------------------------|------------------|---|
| 1a: Understand Modules                          | Written          | 1 |
| 1b: Understand Module Reloading                 | Written          | 1 |
| 1c: Understand Type Hints                       | Written          | 2 |
| 1d: Understand Dict Methods                     | Written          | 1 |
| 1e: Practice Dict Comprehension                 | Code             | 1 |
| 1f: Understand FreqDists                        | Written          | 1 |
| 1g: Unintended Uses of FreqDists                | Written          | 1 |
| 1h: Understand Mutable Objects                  | Written          | 1 EC |
| 2a: Understand Frequency Ratios                 | Written          | 1 |
| 2b: Determine Applicability of Frequency Ratios | Written          | 2 |
| 2c: Implement Smoothing                         | Code             | 2 |
| 2d: Normalize Distributions                     | Code             | 1 |
| 2e: Calculate Frequency Ratios                  | Code             | 2 |
| 2g: Identify Wikipedia Keywords                 | Code and Written | 2 |
| 2h: Limitations of Frequency Ratios             | Written          | 2 |
| 3a: Ask for Help                                | No Submission    | 1 EC |
| 3b: Help a Friend                               | No Submission    | 1 EC |
| **Total**                                       |                  | **20** |

### Rubric for Code Problems
Code questions will be graded using a series of [Python unit tests](https://realpython.com/python-testing/). Each function you implement will be tested on a number of randomly generated inputs, which will match the specifications described in the function docstrings. <!-- **The unit tests will run immediately upon submitting your solution to [Gradescope](https://www.gradescope.com), and you will be able to see the results as soon as the tests have finished running.** Therefore, you are encouraged to debug and resubmit your code if one or more unit tests fail. -->

For code questions, you will receive:
* full points if your code runs and passes all test cases
* at least .25 points if your code runs but fails at least one test case
* 0 points if your code does not run.

Partial credit may be awarded at the Romi's discretion, depending on the correctness of your logic and the severity of bugs or other mistakes in your code. All code problems will be graded **as if all other code problems had been answered correctly**. Therefore, an incorrect implementation of one function should (in theory) not affect your grade on other problems that depend on that function.

### Rubric for Written Problems
For written problems, you will receive:
* full points if your answer is completely correct
* at least .25 points if a good-faith effort (according to Romi's judgment) has been made to answer the question
* 0 points if your answer is blank.

Partial credit may be awarded at Romi's discretion.

## Late Submissions and Resubmissions

Grading will commence on October 5, and solutions will be released on that day. Therefore, no late submissions will be accepted after 9:00 AM on October 5. You may resubmit your solutions as many times as you like; only the final submission will be graded. If the final submission occurs after the deadline on September 28, then your submission will be considered late even if you have previously submitted your solution before the deadline.
