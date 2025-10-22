# Level 2 Quick Reference

## Issue Keywords

Use these keywords in pull requests or commit messages to automatically link and close issues:

| Keyword | Example | Effect |
|---------|---------|--------|
| `Fixes` | `Fixes #42` | Closes issue #42 when PR is merged |
| `Closes` | `Closes #42` | Closes issue #42 when PR is merged |
| `Resolves` | `Resolves #42` | Closes issue #42 when PR is merged |
| `Ref` | `Ref #42` | References issue #42 (doesn't close it) |
| `#` | `See #42` | Creates a link to issue #42 |

**Note**: Keywords are case-insensitive and work in both PR descriptions and commit messages.

## Common GitHub Labels

Default labels available in most repositories:

| Label | Color | Purpose |
|-------|-------|---------|
| `bug` | 🔴 Red | Something isn't working |
| `documentation` | 🔵 Blue | Improvements or additions to documentation |
| `duplicate` | ⚪ Gray | This issue or pull request already exists |
| `enhancement` | 🟢 Green | New feature or request |
| `good first issue` | 🟣 Purple | Good for newcomers |
| `help wanted` | 🟢 Green | Extra attention is needed |
| `invalid` | ⚪ Gray | This doesn't seem right |
| `question` | 🟣 Pink | Further information is requested |
| `wontfix` | ⚪ Gray | This will not be worked on |

## Pull Request Review States

| State | Meaning |
|-------|---------|
| **Comment** | General feedback without explicit approval |
| **Approve** | The changes look good and are ready to merge |
| **Request Changes** | Changes must be made before merging |

## Branch Naming Conventions (Best Practices)

| Type | Format | Example |
|------|--------|---------|
| Feature | `feature/description` | `feature/add-user-login` |
| Bug Fix | `fix/description` | `fix/navigation-error` |
| Hotfix | `hotfix/description` | `hotfix/security-patch` |
| Documentation | `docs/description` | `docs/update-readme` |
| Refactor | `refactor/description` | `refactor/clean-utils` |

## Markdown Quick Reference

Use Markdown in issues, PRs, and comments:

```markdown
# Heading 1
## Heading 2
### Heading 3

**bold text**
*italic text*
~~strikethrough~~

- Bullet list
- Another item

1. Numbered list
2. Another item

[Link text](https://example.com)

`inline code`

\`\`\`python
# code block
def hello():
    print("Hello, GitHub!")
\`\`\`

> Blockquote

| Table | Header |
|-------|--------|
| Cell  | Cell   |

- [ ] Task list item
- [x] Completed task

@mention a user
#123 reference issue or PR

:emoji: (e.g., :rocket: = 🚀)
```

## GitHub CLI Commands (Bonus)

If you have GitHub CLI installed:

```bash
# List issues
gh issue list

# Create an issue
gh issue create --title "Bug: Something broke" --body "Details here"

# List pull requests
gh pr list

# Create a pull request
gh pr create --title "Add feature" --body "Description"

# Review a pull request
gh pr review 42 --approve

# Merge a pull request
gh pr merge 42
```

## Keyboard Shortcuts

While on GitHub.com:

| Shortcut | Action |
|----------|--------|
| `?` | Show all keyboard shortcuts |
| `g` + `i` | Go to Issues |
| `g` + `p` | Go to Pull Requests |
| `g` + `c` | Go to Code |
| `/` | Focus search bar |
| `.` | Open in github.dev editor |
| `e` | Edit file (when viewing) |
| `t` | Open file finder |

## Status Check Icons

| Icon | Meaning |
|------|---------|
| ✅ | Checks passed |
| ❌ | Checks failed |
| 🟡 | Checks pending |
| ⭕ | Checks skipped |

---

**Pro Tip**: Bookmark this page for quick reference while working through Level 2! 🔖
