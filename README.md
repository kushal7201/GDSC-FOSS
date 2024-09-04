# GDSC FOSS WING
## Task Instructions:
Each Task should be committed in `contributors / <your roll number> / <task number> / file.txt`. <br>
**Note:** -  Each commit should have a message that briefly describes the change it introduces. The screenshot required should be saved in the `contributors / <roll number> / <task number> folder` with name <screenshot_number>.png(or jpg or jpeg).
          
## Task-1 Steps

1.  On the `main` branch, add the name of your favorite food to the first line of a designated text file.
   - **Commit:** Save this change with a commit message, such as `"Added favorite food"`.

2.  Create a new branch named `feature`, using the `main` branch as the base.

3.  On the `feature` branch, add the name of your dream company on the second line of the same text file.
   - **Commit:** Save this change with a commit message, like `"Added dream company"`.

4.  Switch back to the `main` branch and add the name of your city on the second line, just below your favorite food.

5.  Commit this change on the `main` branch with a message such as `"Added city name"`.

6.  Merge the `feature` branch into the `main` branch.

7.  Resolve any merge conflicts that arise during the merge process. The final format of the file should be:
   - **First line:** Favorite food
   - **Second line:** City name
   - **Third line:** Dream company

8.  Create a final commit after resolving the merge conflict. Ensure the commit message clearly indicates that the conflict has been resolved.

9.  Capture a screenshot showing all commits made during this task.

10. Push your changes and create a pull request.



## Task-2 Steps

1.  Make three separate changes in your working directory and commit each change individually. Follow the instructions below for each commit:
   - **First Commit:** Write your full name on the first line of the designated text file and commit this change with a message like `"Initial commit with full name."`
   - **Second Commit:** Add your favorite tech stack on the second line of the same text file and commit this change with a message such as `"Added favorite tech stack."`
   - **Third Commit:** Write your hobby on the third line of the file and commit this change with a message like `"Added hobby."`

2.  Perform a soft reset to undo the last two commits, keeping their changes in your working directory as unstaged files. The first commit should remain intact in the commit history. Use the command:
   - **Screenshot 1:** Take a screenshot of the commit history after the reset, highlighting that the first commit is still present, and the changes from the second and third commits are unstaged.

3.  Stage all the unstaged changes from the reset (corresponding to the second and third commits) and combine them into a single final commit.
   - **Final Commit:** Save this commit with a message like `"Combined changes from reset commits."`

4.  Confirm that the final commit reflects the combined changes from the previously reset commits and that the commit history now shows the first original commit followed by the final combined commit.
   - **Screenshot 2:** Capture a screenshot of the final commit history, showing that the changes from the second and third commits have been successfully combined into one commit after the reset.

---

## Required screenshots of Task 2

- **Screenshot 1:** Details of the three commits, showing the first, second, and third commit.
- **Screenshot 2:** After the soft reset, showing the first commit and the unstaged changes.
- **Screenshot 3:** After the final commit, displaying the updated commit history with the combined changes.

