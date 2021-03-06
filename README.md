# Fairness Diagnostic (FD)

CS4145 Crowd Computing Project - Group 9 

Topic: Fairness Preferences for DSS

## Installation instructions
To run the pre- and postprocessing code you will need both python and jupyter notebook.

Firstly install python through https://www.python.org/downloads/.

Once you have installed python run the following command and you should be ready to run the code:
```pip install -r requirements.txt```
	
## Contents of the directories
We used [Amazon Mechanical Turk Sandbox](https://workersandbox.mturk.com/) to help us design crowdsourcing tasks. 

The projects design layout HTMLs of the scenarios are in the [MTurk_projects](https://github.com/SunweiWang/CrowdComputing/tree/master/MTurk_projects) folder. The output data from MTurk and the feedback is in the [data](https://github.com/SunweiWang/CrowdComputing/tree/master/data) folder.

The folder [sessions](https://github.com/SunweiWang/CrowdComputing/tree/master/sessions) contains the images and generator of the input data to MTurk projects and the folder [postprocessing](https://github.com/SunweiWang/CrowdComputing/tree/master/postprocessing) contains
a jupyter notebook which handles the data from the MTurk to obtain useful data. 

## Instruction to the participants

1. Please first go to https://workersandbox.mturk.com/
2. Create an Amazon account with your email
3. After creating the account, log in, click on  https://workersandbox.mturk.com/requesters/A1SW5OZA9ST70H/projects
4. You should see following two tasks:
![original image](https://cdn.mathpix.com/snip/images/eyrt66IZ3pQvby6lEw24HVT8WletcCjMe0H9OdfahNw.original.fullsize.png)

5. The first task (Criminal Justice) have 8 tests, the second task (Toxic Comment) have 7 tests, please complete all 15 tests for both tasks.
6. When click Accept & Work for the first task, you will see following interface:
![original image](https://cdn.mathpix.com/snip/images/8KS6yX6MfYQHAiuXJphmC-U2g-_6cFVI_Xlt4xvKZKk.original.fullsize.png)

7. Check the box for Auto-accept next HIT.
8. Read the Motivation and instruction, after finishing test of the task, you can submit the test by clicking on submit button at the end of the page. 

