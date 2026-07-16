# Practice

## Git Undo Rules

1. `git restore --staged file-name` removes a file from staging.
2. Unstaging does not delete the file content.
3. `git restore file-name` discards unstaged changes.
4. Restore is dangerous if the change is not saved in a commit.
5. Always run `git status` after undo commands.