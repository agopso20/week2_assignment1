# Introduction to group coding exercises
You will form groups of four and work on this exercise together, submitting a single code at the end of the class period. You will work together on exercises in the same groups each Thursday this quarter. Introduce yourselves and and decide among yourselves which roles you would like to undertake. Note that you cannot have the same role two weeks in a row, and you must fill each role at least once during the quarter.

## Roles and Responsibilities:

1. Developer: Person who types the code and submits it to Gradescope at the end of the class period.

2. Reporter: Responsible for communicating with instructors, writing exercise reflection, and keeping any written notes.

3. Researcher: Search slides, notes, and internet for solutions to coding problems.

4. Documenter: Make sure code is adequately commented. Make sure any code solutions used from an online source like Stack Overflow are clearly noted and cited to avoid plagiarism.

**In-class coding exercise #1** <br>
Objective: This exercise introduces you to writing Python code in Jupyter notebooks and builds familiarity with variables and math operations, debugging code, and manipulating strings.

Instructions:

1. Assign group roles and note in the Gradescope submission which who filled which roles.
2. The group developer will clone the code from the GitHub repository, then open in JupyterHub. (see step 3 for more details). Don't forget to make a personal repository and add your group members as collaborators. You can do this by going to the repository settings (top panel) and selecting "Collaborators and Teams" under the "Access" section.
3. In your JupyterHub terminal, change to your home directory. Run this line of code to clone the public class repository into your local server:
> ``` git clone git@github.com:OCEAN-215-2023/week2_inclass.git ```
4. Sometimes, our JupyterHub server has trouble remembering the file permissions for our SSH keys. If you get a file permission error with your private ssh key, run this line of code:
> ```chmod 400 ~/.ssh/id_ed25519```
5. There should now be a "week2_inclass" directory in the home directory of your JupyterHub. In terminal, change directories into "homework_1". Next, click on the the "homework_1" icon on the filepath hierarchy in the left panel of JupyterHub. If you don't see it, make sure you're in the home folder by clicking the folder icon under the search bar.
6. In terminal, set your branch to main (step 17 in #0b) and your remote (origin) to your **_personal_** "week2_inclass" GitHub repository (step 18).
7. Double click the "group_activity1.ipynb" to open it in a new tab and begin working on the assignment.
8. Create a README file and write your name and UW NetID. You should also include other information, such as your group member names and how you used git to add, commit, and push to your GitHub.
9. As you continue to answer the homework questions and make edits to your code, make sure to regularly update your GitHub repository as well via git add, commit, and push (steps 15, 16, 19 in #0b). A good rule of thumb would be to run these git steps anytime you make an addition or change that you don't want to accidentally lose. Generally, you can push once a day to maintain good version control.
10. Complete the assignment together by writing and executing text and code cells as specified. For this assignment, do not use any features of Python that have not yet been discussed in the lessons or class sessions.
11. Discuss the reflection questions at the end of the exercise. The group reporter will type concise answers to each in the provided text box.
12. When you're finished and are ready to submit the exercise, the group developer will push the completed notebook it to GitHub and submit to Gradescope. Make sure to remember to add your other group members in Gradescope! No submission is necessary from other group members.
