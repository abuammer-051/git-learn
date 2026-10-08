# Git Learning Practice - Right Branch

This repository records practical exercises for Git Tutorial sections 3 and 4.

## 3. Branching and Merging

- Push a branch: `git push -u origin <branch>`
- Delete branches: `git branch -d <branch>` and `git push origin --delete <branch>`
- Checkout/switch and merge: `git switch <branch>`, `git merge <branch>`
- Resolve merge conflicts by editing conflicted files, staging them, and committing
- Rebase: `git rebase main`
- Squash: `git rebase -i HEAD~N` or use **Squash and merge** in a pull request
- Fork: create a copy under another account or organization, then contribute through a pull request

## 4. File and Change Management

- Compare changes: `git diff`, `git diff --staged`
- Remove ignored/untracked work safely: preview with `git clean -n`, then use `git clean -f`
- Rename or move: `git mv old-name new-name`
- Undo a commit safely: `git revert <commit>`
- Restore work: `git restore <file>` or `git restore --staged <file>`
- Stage changes: `git add <file>`
- Remove untracked files: preview with `git clean -n` before deleting
- Track an otherwise empty directory by adding a `.gitkeep` file

## Evidence in this repository

The pull requests and commit history demonstrate remote branches, diffs, merges, squash/rebase strategies, file movement, conflict handling, undo/revert, and temporary branch cleanup. Git staging, clean, and removal of local untracked files are local working-tree operations, so their safe commands are documented above.
