## Unit 0 Error Patterns

### Folder and command mistakes
- Created a folder when intending to create a file by using `mkdir` instead of `ni`.
- Misspelled folder names such as `projects-records` and `comflict`.
- Forgot spacing in commands, such as writing `cd../..` instead of `cd ../..`.

### Git workflow mistakes
- Tried to stage a file using the wrong path from the current terminal location.
- Used `git add .` and accidentally staged tool-generated `.vscode/settings.json`.
- Saw confusing diff output caused by missing newline at the end of a file.
- Needed to distinguish `git diff`, `git diff --cached`, `--stat`, and `--name-only`.

### Prevention rules
- Always check `pwd` and `dir` before creating files.
- Always run `git status` before and after Git actions.
- Inspect changes before committing.
- Use `git restore` only after checking `git diff`.
- Be careful with `git add .` because it can stage unintended files.