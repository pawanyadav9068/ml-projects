Commands to run in terminal (from Home directory)
mkdir ml_project
cd ml_project

1- Creates project folder and enters it

git init

2- Initializes empty Git repository

touch train.py predict.py utils.py README.md

3- Creates required files

git add .

4- Stages all files for commit

git commit -m "Initial project setup with empty files"

5- Saves first version of project

Add training code, commit, connect GitHub, push
git status

1- Check current repo state

git add train.py utils.py

2- Stage updated training files

git commit -m "Added training script and helper utilities"

3- Save changes locally

git branch -M main

4-Ensure branch name is main

git remote add origin https://github.com/username/ml-project.git

5- Connect local repo to GitHub repo

git push -u origin main

 Upload project to GitHub

 Teammate updated predict.py and README.md

updated utils.py and config.py

 Check current changes

git status
 
 Shows modified files
 
 Stage changes

git add utils.py config.py

Stage your work

Commit  changes

git commit -m "Updated utilities and configuration settings"

Save your work locally

Pull latest teammate updates

git pull origin main

Push final project

git push origin main
 
 Uploads  final version to GitHub

