git config user.name "CARL ANDREI A. DAGUPLO"
git config user.email "carlandrei.daguplo@cvsu.edu.ph"

git config user.name
git config user.email

git init

git branch -M main

git add index.html
git commit -m "Initial commit - plain HTML page"

git branch no-style

git switch main

git add .
git commit -m "Add CSS styling and JavaScript interactivity"

git log --oneline --decorate --all

git remote add origin https://github.com/carlandreidaguplo-collab/Lab-1-Git-GitHub-and-Branching.git

git remote -v

git push -u origin main

git push -u origin no-style

git branch -a

git status

git log --oneline --decorate --all
