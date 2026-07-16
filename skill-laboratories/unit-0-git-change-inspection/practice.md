# Practice

## Git Inspection Rules

1. `git status` shows which files changed.
2. `git diff` shows the exact content changes.
3. `git diff --name-only` shows only the changed file names.
4. I should inspect changes before committing.
5. I should not commit files I did not intend to change.

## Personal Rule

Before every commit, I will run:

`git status`

Then, when needed:

`git diff`

## Personal Inspection Rule

Before I commit, I must check:
- `git status`
- `git diff` if there are unstaged changes
- `git diff --cached --stat` if there are staged changes