## Step 9: Merge and see the issue close

_Fantastic review work! :eyes:_

You've reviewed the pull request and approved it. Now let's see the magic of GitHub automation when you merge a pull request that references an issue!

**What happens when you merge?**: When you merge a pull request that contains keywords like `Fixes #1` or `Closes #2`, GitHub automatically:
- Closes the referenced issue
- Links the pull request to the issue
- Creates a complete audit trail from issue to implementation

This automation helps keep your project organized without manual effort!

### :keyboard: Activity: Merge and verify issue closure

1. Navigate to your pull request (the `add-favorite-color` branch).

2. Scroll down to the bottom of the **Conversation** tab.

3. Click the green **Merge pull request** button.

4. Click **Confirm merge**.

5. After merging, you can safely delete the branch by clicking **Delete branch**.

6. Now, navigate to the **Issues** tab to see what happened to your issue.

7. You should notice that the issue you created (about adding favorite color) is now closed automatically! ✨

   > **Note:** The issue will show as "Closed" and have a purple merged pull request icon next to it, indicating it was closed by merging a PR.

8. Click on the closed issue to view it. You'll see a reference showing which pull request closed it.

9. Once you've verified that your issue was automatically closed by the merge, Mona will check your progress and provide the final lesson!

<details>
<summary>Having trouble? 🤷</summary><br/>

If you don't get feedback, here are some things to check:
- Verify you merged the pull request completely
- Make sure your commit or PR description included `Fixes #` with your issue number
- Check the Issues tab - look in the Closed section if you don't see your issue in Open
- Confirm the issue shows as closed (not just filtered out)

</details>
