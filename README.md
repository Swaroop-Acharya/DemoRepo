# DemoRepo


git init 
touch file.txt
git add .
git commit -m ""
git status
git log


touch file2.txt
git add .
git restore --staged file2.txt

git add .
git commit -m ""

git reset 11ca96088d1f88a21d3a770cf2a081fd7957ae6f

//reset will be unstaged 

git add .

//putting in stash

git stash

//now changes will be stash

// to bring back changes

git stash pop

// to clear stash entry

git stash clear


git commit -m " "



git branch feature
git checkout feature
touch button.txt
git add .
git commit -m ""
git status

git checkout main
git merge feature
git status
git log



//Forkl,clone, pull 
