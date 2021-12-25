# Test repo -- introduction to Git Bash
# Test ReadMe
# Test

# GIT COMMANDS: 
git init
git add [file name] or .
git status
git commit -m "message"
git checkout -b "BRANCH NAME" (make a new branch or switch branch)


# TO MERGE BRANCH: 
git checkout "BRANCH NAME"
add >> status >> commit
git push origin "BRANCH NAME"
git fetch origin
git merge master
fix any conflicts on local file, if any >> add >> status >> commit >> fetch origin
git merge master

git checkout master
git merge --no-ff "BRANCH NAME"
git push origin master


