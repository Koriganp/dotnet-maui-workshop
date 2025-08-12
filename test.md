# Committing

## 1) Go to your project folder

cd "C:\Users\koriganp\OneDrive - Willie George Ministries\projects\YOUR-PROJECT-FOLDER"

## 2) See what’s changed

git status

## 3) If this is a new repo (skip if already initialized)

git init
git branch -M main

## 4) Stage and commit your changes

git add -A
git commit -m "Your commit message"

## 5) Add the GitHub remote (pick one)

### HTTPS

git remote add origin <https://github.com/USERNAME/REPO.git>

### or SSH

### git remote add origin <git@github.com>:USERNAME/REPO.git

## 6) Push and set upstream

git push -u origin main
