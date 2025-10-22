# Level 2 Training Workflow

## Visual Overview

```
┌─────────────────────────────────────────────────────────────────┐
│                    LEVEL 2: Intermediate GitHub                 │
└─────────────────────────────────────────────────────────────────┘

┌─────────────────┐
│  Step 0: Start  │
│   Level 2       │ ← Create issue "Start Level 2 Training"
│                 │   OR trigger workflow manually
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  Step 5:        │
│  Create Issue   │ ← Create issue: "Add favorite color to profile"
│                 │   with description and task list
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  Step 6:        │
│  Add Labels     │ ← Add label (e.g., "enhancement")
│                 │   to the issue you created
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  Step 7:        │
│  Reference      │ ← Create branch: add-favorite-color
│  Issue in PR    │   Edit PROFILE.md
│                 │   Commit with: "Fixes #1"
│                 │   Create pull request
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  Step 8:        │
│  Review PR      │ ← Add line comment on Files changed
│                 │   Submit approval review
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  Step 9:        │
│  Merge & Close  │ ← Merge the pull request
│  Issue          │   Issue auto-closes! ✨
└────────┬────────┘
         │
         ↓
┌─────────────────┐
│  🎉 Complete!   │
│  Level 2 Review │ ← Congratulations message
│                 │   Next steps suggestions
└─────────────────┘
```

## Step-by-Step Flow Details

### Pre-requisite: Complete Level 1
Before starting Level 2, you should have completed:
- ✅ Step 1: Create a branch
- ✅ Step 2: Commit a file
- ✅ Step 3: Open a pull request
- ✅ Step 4: Merge your pull request

---

### Step 5: Create an Issue
**What you'll do:**
1. Navigate to Issues tab
2. Click "New issue"
3. Title: `Add favorite color to profile`
4. Add description with task list
5. Submit the issue

**What you'll learn:**
- Why issues are important for planning
- How to write effective issue descriptions
- Using task lists in Markdown

**Trigger:** Issue created with correct title
**Next:** Workflow posts Step 6 instructions

---

### Step 6: Work with Labels
**What you'll do:**
1. Open your issue from Step 5
2. Click the gear icon next to "Labels"
3. Select "enhancement" (or another label)
4. Label is applied to the issue

**What you'll learn:**
- How labels help organize work
- Default GitHub labels and their purposes
- Filtering issues by labels

**Trigger:** Label added to the issue
**Next:** Workflow posts Step 7 instructions

---

### Step 7: Reference Issue in PR
**What you'll do:**
1. Create branch: `add-favorite-color`
2. Edit `PROFILE.md` file
3. Add favorite color section
4. Commit with message including `Fixes #1` (your issue number)
5. Create pull request
6. Add issue reference in PR description

**What you'll learn:**
- Linking issues to code changes
- Keywords that auto-close issues (Fixes, Closes, Resolves)
- Best practices for commit messages

**Trigger:** PR created with branch `add-favorite-color` and issue reference
**Next:** Workflow posts Step 8 instructions

---

### Step 8: Review Pull Request
**What you'll do:**
1. Navigate to your PR
2. Click "Files changed" tab
3. Add comment on specific line
4. Go to "Conversation" tab
5. Click "Review changes"
6. Select "Approve"
7. Submit review

**What you'll learn:**
- How to review code changes
- Adding inline comments
- Approval workflow
- Pull request review states

**Trigger:** Approved review submitted on PR
**Next:** Workflow posts Step 9 instructions

---

### Step 9: Merge and Close Issue
**What you'll do:**
1. Navigate to your PR
2. Click "Merge pull request"
3. Click "Confirm merge"
4. Delete the branch
5. Check Issues tab - issue is auto-closed!

**What you'll learn:**
- Merging pull requests
- GitHub's automation features
- How issue keywords work
- Clean-up after merging

**Trigger:** PR merged to main
**Next:** Workflow posts completion review

---

## Automation Flow

```
User Action          GitHub Workflow        Result
─────────────        ───────────────        ──────

Create Issue    →    5-create-an-issue    →  Posts Step 6
                     (validates title)

Add Label       →    6-work-with-labels   →  Posts Step 7
                     (detects labeled event)

Create PR       →    7-reference-issue    →  Posts Step 8
                     (checks references)

Approve Review  →    8-review-pr          →  Posts Step 9
                     (verifies approval)

Merge PR        →    9-merge-and-close    →  Posts Review
                     (confirms merge)         Completes!
```

## Key Concepts Demonstrated

1. **Project Planning**: Using issues to plan before coding
2. **Organization**: Labels for categorization
3. **Traceability**: Linking issues and PRs
4. **Quality**: Code review process
5. **Automation**: Auto-closing issues on merge

## Common Workflows Patterns

This training teaches patterns used in real-world development:

| Pattern | When to Use | Example |
|---------|-------------|---------|
| Issue First | Planning new work | Create issue, discuss, then implement |
| Label Strategy | Large projects | bug/enhancement/documentation labels |
| Issue References | All PRs | "Fixes #42" in commit/PR |
| PR Reviews | Team collaboration | All changes reviewed before merge |
| Auto-close | Completing work | Merging PR closes related issues |

---

**Ready to start?** Head to the [Level 2 Guide](LEVEL-2-GUIDE.md) for instructions!
