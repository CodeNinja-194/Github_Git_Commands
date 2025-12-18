# Git Commands Reference Guide

This repository contains a quick reference for commonly used Git commands, from basics to advanced usage.


## Repository Setup
bash
git init
git clone <repository_url>

## Checking Status & History
git status
git log
git log --oneline
git log --oneline --graph --all
git diff

## Staging Files
git add <file_name>
git add .
git restore <file_name>
git restore --staged <file_name>

## Committing Changes
git commit -m "commit message"
git commit -a -m "commit message"
git commit --amend
git commit --amend --no-edit

## Branching
git branch
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
git switch <branch_name>
git switch -c <branch_name>

## Merging Branches

git merge <branch_name>

## Handling Merge Conflicts
git status
 #Resolve conflicts manually in files
git add <file_name>
git commit

## Remote Repository Commands
git remote -v
git remote add origin <url>
git fetch
git pull
git push origin <branch_name>

## SSH (Authentication)

ssh-keygen -t ed25519 -C "email@example.com"
ssh -T git@github.com
