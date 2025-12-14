# 4787SS
Repo for git task (softserve course)

This repository is created for practicing Git and GitHub workflows, including SSH key authentication, Personal Access Tokens (PAT), branch management, and Pull Requests.

## Repository Structure

- `bash.sh` — Bash script used in exercises.
- `new_file` — File created in `scripts-new-merge-features` branch with author's name.

## Branches

- `main` — Initial branch, contains basic repository files.
- `scripts` — Branch where `bash.sh` is added.
- `scripts-new-features` — Branch for adding new features to `bash.sh`.
- `scripts-new-merge-features` — Branch for creating a new file (`new_file`) and merging back into `scripts`.

## Workflow Summary

1. **SSH Key Setup**
   - Generated an SSH key specifically for this GitHub account.
   - Added the key to GitHub account settings.
   - Verified SSH access with `ssh -T git@github.com`.

2. **Personal Access Token (PAT)**
   - Created a PAT with `repo` and `workflow` scopes.
   - Used for authentication in CLI if needed.

3. **Repository Setup**
   - Cloned the repository to local machine using SSH.
   - Configured Git with `user.name` and `user.email`.

4. **Branch Management**
   - Created `scripts` branch and added `bash.sh`.
   - Created `scripts-new-features` branch, modified `bash.sh` to add `echo 'The practice started'`.
   - Pushed branches to GitHub and created a Pull Request for `scripts-new-features` into `scripts`.
   - Created `scripts-new-merge-features` branch, added `new_file` with author's name, and merged it into `scripts`.

5. **Verification**
   - Verified commits and merges using `git log --oneline --graph --decorate`.
   - Ensured all branches are present on GitHub and Pull Requests completed.

## How to Use

1. Clone the repository:

```bash
git clone git@github.com:fry88/4787SS.git
cd 4787SS