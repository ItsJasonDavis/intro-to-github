# Level 2 Training Guide

## Introduction to GitHub - Level 2: Intermediate Collaboration

This Level 2 training builds on the foundation from Level 1 and teaches intermediate GitHub collaboration features. You'll learn how to use issues, labels, reviews, and automation to work more effectively with teams.

## Prerequisites

Before starting Level 2, you should have completed Level 1, which covers:
- Creating branches
- Making commits
- Opening pull requests
- Merging pull requests

## What You'll Learn

Level 2 covers five key intermediate topics:

### Step 5: Create an Issue
Learn how to use GitHub Issues to track work, bugs, and feature requests before writing code.

### Step 6: Work with Labels
Organize and categorize your issues using labels for better project management.

### Step 7: Reference Issues in Pull Requests
Connect your code changes to the issues they address using special keywords like `Fixes #1`.

### Step 8: Review Pull Requests
Practice providing feedback on code changes and approving pull requests.

### Step 9: Merge and Auto-Close Issues
See GitHub's automation in action as issues are automatically closed when referenced PRs are merged.

## How to Start Level 2

There are two ways to start the Level 2 training:

### Option 1: Create an Issue (Recommended)
1. Navigate to the **Issues** tab in your repository
2. Click **New issue**
3. Title: `Start Level 2 Training`
4. Description: Add any notes you want
5. Click **Submit new issue**

The workflow will automatically detect this issue and post the first lesson (Step 5).

### Option 2: Manual Workflow Trigger
1. Navigate to the **Actions** tab in your repository
2. Select **Step 0 - Start Level 2** from the workflows list
3. Click **Run workflow**
4. Select the branch (usually `main`)
5. Click **Run workflow**

An issue will be created automatically, and the first lesson will be posted.

## Exercise Flow

Each step follows this pattern:

1. **Read the Instructions**: Each step provides clear guidance on what to do
2. **Complete the Task**: Follow the step-by-step instructions
3. **Automatic Verification**: GitHub Actions workflows check your work
4. **Get Feedback**: Mona (the automated assistant) provides feedback in the issue
5. **Move to Next Step**: Once verified, the next lesson is automatically posted

## Tips for Success

- **Read Carefully**: Each step builds on the previous one
- **Take Your Time**: There's no rush - learn at your own pace
- **Ask for Help**: If you get stuck, check the troubleshooting sections in each step
- **Practice Multiple Times**: Feel free to repeat any step to reinforce learning
- **Explore More**: Try variations of what you learn to deepen understanding

## Workflow Status Badges

Track your progress with the workflow status badges shown in the README:

- 🔴 Red badge = Workflow hasn't run yet or failed
- 🟡 Yellow badge = Workflow is running
- 🟢 Green badge = Step completed successfully

## Troubleshooting

### Issue not being detected
- Make sure the issue title exactly matches `Add favorite color to profile`
- Verify you're in the correct repository
- Check that the workflow is enabled in the Actions tab

### Workflow not running
- Workflows may be disabled by default - enable them in the Actions tab
- Check the workflow triggers match your actions
- Ensure you have proper permissions

### Pull request not connecting to issue
- Use keywords like `Fixes #1`, `Closes #1`, or `Resolves #1`
- Make sure the issue number is correct
- Include the reference in either the PR description or commit message

## After Completing Level 2

Once you've completed all five steps, you'll have learned:
- ✅ How to plan work using issues
- ✅ How to organize projects with labels
- ✅ How to connect issues and code changes
- ✅ How to review and approve changes
- ✅ How GitHub automation streamlines workflows

### Next Steps

Continue your GitHub journey:
- **GitHub Projects**: Learn visual project management
- **GitHub Actions**: Automate your development workflow
- **Protected Branches**: Require reviews before merging
- **Code Owners**: Set up automatic review requests
- **Contributing to Open Source**: Apply your skills to real projects

## Resources

- [GitHub Skills](https://skills.github.com) - More learning exercises
- [GitHub Docs](https://docs.github.com) - Official documentation
- [GitHub Community Discussions](https://github.com/community) - Get help and share knowledge

---

Happy learning! 🚀
