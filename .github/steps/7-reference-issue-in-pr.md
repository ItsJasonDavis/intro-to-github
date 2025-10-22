## Step 7: Reference an issue in a pull request

_Excellent work with labels! :label:_

Now let's connect your issue to actual work. One of GitHub's powerful features is the ability to link issues and pull requests, creating a clear trail from problem to solution.

**What is issue referencing?**: You can reference issues in pull requests, commits, and other issues using special keywords. When you merge a pull request that references an issue with certain keywords (like `fixes #1` or `closes #2`), GitHub automatically closes the related issue.

**Why reference issues?**: This creates better project documentation by:
- Showing which code changes address which issues
- Automatically closing issues when work is merged
- Creating a traceable history of decisions and implementations
- Helping team members understand the context of changes

### :keyboard: Activity: Create a branch and reference the issue

Let's implement the feature described in your issue!

1. Navigate to the **< > Code** tab.

2. Click on the **main** branch drop-down.

3. In the text box, type `add-favorite-color` to create a new branch.

4. Click **Create branch: add-favorite-color from main**.

5. Now that you're on the new branch, click on the `PROFILE.md` file to open it.

6. Click the pencil icon ✏️ to edit the file.

7. Add the following content to the end of the file:

   ```
   
   ## Favorite Color
   
   My favorite color is blue! 💙
   ```

   > **Tip:** Feel free to use your actual favorite color!

8. Scroll down to the commit section. In the commit message, type:
   
   ```
   Add favorite color section
   
   Fixes #1
   ```
   
   > **Important:** Replace `#1` with your actual issue number if different. The `Fixes #1` keyword tells GitHub to automatically close issue #1 when this commit is merged to main.

9. Make sure **Commit directly to the add-favorite-color branch** is selected.

10. Click **Commit changes**.

11. After committing, create a pull request for this branch:
    - Click on **Pull requests** tab
    - Click **New pull request**
    - Select `add-favorite-color` as the compare branch
    - Click **Create pull request**
    - In the description, add `This PR addresses #1` (replace with your issue number)
    - Click **Create pull request**

12. Once your pull request is created with the issue reference, Mona will check your work!

<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, here are some things to check:
- Verify your commit message includes `Fixes #` followed by your issue number
- Make sure your pull request description references the issue with `#` and the number
- Confirm you created the branch named `add-favorite-color`
- Check that you edited the `PROFILE.md` file

</details>
