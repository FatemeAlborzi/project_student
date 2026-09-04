# Student Project

## Description

This is a simple Python project created to practice practical Git and GitHub workflows.
The project demonstrates local repository management, version control, branching, remote repositories,
collaboration concepts, merge conflict resolution, and SSH-based GitHub authentication.

## Project Files

- `main.py` — contains the basic Python output used throughout the Git exercises.
- `student.py` — contains sample student information used for branch and feature exercises.
- `README.md` — explains the project, how to run it, and the Git concepts practiced.

## How to Run

Make sure Python is installed, then open a terminal in the project directory and run:

```bash
python main.py
```

To run the student information file:

```bash
python student.py
```

## Git Concepts Used

- Creating a local Git repository with `git init`
- Checking repository status with `git status`
- Reviewing changes with `git diff`
- Staging files with `git add`
- Creating commits with `git commit`
- Editing the latest commit with `git commit --amend`
- Viewing commit history with `git log` and `git log --oneline`
- Creating and switching branches
- Merging branches
- Using `git stash` to temporarily store uncommitted changes
- Understanding `git revert` and `git reset`
- Adding a remote repository with `git remote add origin`
- Checking remotes with `git remote -v`
- Pushing local branches to GitHub
- Setting an upstream branch with `git push -u`
- Cloning a repository with `git clone`
- Pulling remote changes with `git pull`
- Working with remote-tracking branches
- Creating and resolving a merge conflict
- Working with Public and Private GitHub repositories
- Understanding Collaborator access
- Using Git Credential Manager for HTTPS authentication
- Creating an SSH key and adding the public key to GitHub
- Testing SSH authentication with GitHub
- Changing the Git remote URL from HTTPS to SSH

## Authentication Notes

GitHub does not use the normal account password for Git operations over HTTPS.
A Personal Access Token (PAT) is safer because its permissions can be limited,
it can have an expiration date, and it can be revoked without changing the
GitHub account password.

For SSH authentication, GitHub uses a public/private key pair.
The public key can be added to GitHub, while the private key must always remain
secret and must never be committed to a repository.

This project also uses an SSH remote for GitHub authentication.

## Repository

Repository name: `project_student`

## Public, Private and Collaborator

- A Public repository can be viewed by anyone.
- A Private repository can only be accessed by the owner and authorized users.
- A Collaborator has permission to contribute to the repository, while a normal visitor of a Public repository can only view or clone it unless additional permissions are granted.

## GitHub Authentication

GitHub does not use the normal account password for Git operations over HTTPS.
Personal Access Tokens provide more secure and limited access and can be revoked without changing the account password.

SSH authentication uses a public/private key pair.
Only the public key is added to GitHub, and the private key must never be shared or committed to a repository.

## Author

Fateme Alborzi
