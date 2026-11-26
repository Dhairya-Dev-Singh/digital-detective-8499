# Mission 6 — Git and GitHub

Study draft: verify these steps in your repository and rewrite the explanations in your own words before submitting.

## 1. Task / objective

Practise checking repository status, staging and committing changes, viewing commit history, creating a branch, pushing it to GitHub, and opening a pull request.

## 2. Work completed

- Checked the repository status and recent commit history.
- Committed a progress update to the root README (`cea1bfc`).
- Created and pushed the `update-about` branch with a **My Learning** section (`48b3ce8`).
- Opened [pull request #1](https://github.com/Dhairya-Dev-Singh/digital-detective-8499/pull/1) from `update-about` into `main`. It is open and has not been merged.
- Recorded the task notes and a Git command glossary in [Mission-06.txt](Mission-06.txt).

## 3. Commands / tools used

- `git status` — check the current branch and working tree.
- `git add README.md` — stage the README change.
- `git commit -m "..."` — record staged changes.
- `git log -3 --oneline` — view recent commits.
- `git switch -c update-about` — create and switch to a branch.
- `git push -u origin update-about` — publish the branch to GitHub.
- GitHub pull request page — compare `update-about` with `main` and open PR #1.

## 4. My understanding

Git keeps a history of changes in commits. Branches let me work separately, and a pull request asks for review of changes before merging. Rewrite this explanation in your own words before submission.

## 5. Difficulties faced

No major issue was recorded. I checked that GitHub showed `main` as the base and `update-about` as the compare branch.

## 6. How I resolved them

I checked the branch comparison on GitHub before opening the pull request.

## 7. Evidence / files

- [Mission-06.txt](Mission-06.txt) — task-by-task notes and Git command glossary.
- [Root README](../README.md) — progress and learning notes.
- [Pull request #1](https://github.com/Dhairya-Dev-Singh/digital-detective-8499/pull/1) — open review page.

## 8. Commit details

- `cea1bfc` — `Update README before Git workflow`.
- `48b3ce8` — `Add My Learning section to README`.
- Mission 6 documentation will be committed on `update-about` and pushed to update the open pull request.
