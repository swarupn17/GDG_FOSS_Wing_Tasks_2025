# GDG_FOSS_Wing_Tasks_2025

## Prerequisites : 
Ensure that Git is installed on your computer, along with Git Bash for Windows. To complete the tasks, follow these steps:

- `Fork the Repository:` Fork the GDG-FOSS repository to your GitHub account.
- `Clone the Repository:` Clone your forked repository to your local machine.
- `Create a New Branch:` Switch to a new branch named after your roll number.
- `Make Changes:` Implement the required changes in the new branch.
- `Push Changes:` Push the changes to your forked repository on GitHub.
- `Create a Pull Request:` Open a pull request from your branch to the main branch of the GDG-FOSS repository.

Note: You should `create separate pull requests` for each task. If your task meets the specified instructions and is correct, it will be merged into the `main` branch of the repository. Each pull request should be from a branch whose name is `<your roll number> - <task number>`.  For those who have already made pull request before instruction update, if it meets the requirements it will be merged.

## Task Instructions:
Each Task should be committed in `contributors / <your roll number> / <task number> / file.txt`. <br>
**Note:** 
- Each commit should have a message that briefly describes the change it introduces. The screenshot required should be saved in the `contributors / <roll number> / <task number> folder` with name <screenshot_number>.png(or jpg or jpeg). <br>
- You have to use `git log` or `git log --oneline` command in git bash for the screenshots and NOT from the github interface.
- The Pull Request should NOT contain any redundant commits, i.e. only the meaningful commits will be accepted.
          
## Task-1 Steps

1.  On your created branch, add the name of your favorite food to the first line of a designated text file.
   - **Commit:** Save this change with a commit message, such as `"Added favorite food"`.

2.  Create a new branch named `second_branch`, using the initial branch as the base.

3.  On the `second_branch` branch, add the name of your dream company on the second line of the same text file.
   - **Commit:** Save this change with a commit message, like `"Added dream company"`.

4.  Switch back to the initial branch and add the name of your city on the second line, just below your favorite food.

5.  Commit this change on your initial branch with a message such as `"Added city name"`.

6.  Merge the `second_branch` branch into your initial branch.

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

2.  Perform a soft reset to undo the last two commits, keeping their changes in your working directory as unstaged files. The first commit should remain intact in the commit history. 

3.  Stage all the unstaged changes from the reset (corresponding to the second and third commits) and combine them into a single final commit.
   - **Final Commit:** Save this commit with a message like `"Combined changes from reset commits."`

4.  Confirm that the final commit reflects the combined changes from the previously reset commits and that the commit history now shows the first original commit followed by the final combined commit.

---

### Required screenshots of Task 2

- **Screenshot 1:** Details of the three commits, showing the first, second, and third commit.
- **Screenshot 2:** After the soft reset, showing the first commit and the unstaged changes.
- **Screenshot 3:** After the final commit, displaying the updated commit history with the combined changes.

## Task-3 (Advanced Git & Collaboration)

This task is designed to test your advanced Git skills such as amending commits, rebasing, and resolving conflicts. Please follow the steps carefully.

---

### Steps:

1. **Create contribution file**
   - On your created branch `<your roll number>-3`, create a new file:  
     `contributors/<your roll number>/3/contribution.txt`
   - Write **a short introduction about yourself (3–4 lines)** in this file.
   - Commit with a message:  
     ```
     Added self introduction
     ```

2. **Create a new feature branch**
   - Create a new branch named `feature_branch` from `<your roll number>-3`.
   - In the same file (`contribution.txt`), add **one open-source project or idea** you’d like to work on.
   - Commit with message:  
     ```
     Added open-source project idea
     ```

3. **Amend commit**
   - While still on `feature_branch`, amend the last commit to also include **your GitHub username** in the same file.
   - Use:  
     ```
     git commit --amend
     ```

4. **Switch back to main working branch**
   - Switch to your `<your roll number>-3` branch.
   - Add **your favorite programming language** to the same file (`contribution.txt`).
   - Commit with message:  
     ```
     Added favorite programming language
     ```

5. **Rebase feature branch**
   - Rebase the commits from `feature_branch` on top of `<your roll number>-3`.
   - During rebase, resolve any merge conflicts properly so that the final file contains **all four entries**:
     - Self introduction
     - Favorite programming language
     - Open-source project idea
     - GitHub username

6. **Finalize**
   - After resolving conflicts, complete the rebase.
   - Push your `<your roll number>-3` branch.
   - Create a Pull Request from `<your roll number>-3` to the main branch.

---

### Required Screenshots:

- **Screenshot 1**: Commit history before rebasing.  
- **Screenshot 2**: Rebase conflict resolution (screenshot of your terminal).  
- **Screenshot 3**: Final clean commit history after rebase.  
- **Screenshot 4**: Final `contribution.txt` content showing all four entries.  

---

⚠️ **Important Notes**
- Make sure each commit message is meaningful.  
- Do not push redundant commits.  
- Ensure your Pull Request only contains the commits related to this task.  


**Note: Plagiarism will be strictly checked. So please refrain from copying.**
All the best! 👍

