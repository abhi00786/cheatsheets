#Git Common Commands Cheatsheet
#Initialization & Setup

git init — Initialize a new local repository

git config --global user.name "Your Name" — Set your Git username

git config --global user.email "you@example.com" — Set your Git email address

#Basic Workflow

git status — Show current changes/staging info

git add <file> — Add a file to the staging area

git add . — Add all files to the staging area ( From Untracked to Staged)

git commit -m "message" — Commit staged changes with a message ( From Staged to Tracked)

#Remote Repositories

git remote add origin <repo-url> — Link local repo to a remote

git push origin master — Push local commits to remote repo (first push)

git pull — Fetch and merge changes from remote

#Branching

git branch — List all branches

git branch <branchname> — Create new branch

git checkout <branchname> — Switch branch

git merge <branchname> — Merge another branch into current one

#Viewing & Undoing

git log — Show commit history

git diff — Show unstaged changes


git checkout -- <file> — Revert file to last commit
