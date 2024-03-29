
# DIO | Git e GitHub

Repository about Git and GitHub course from DIO.

## 📚 Documantation
- [Documentação Git](https://git-scm.com/doc) 
- [Documentação GitHub](https://docs.github.com/)

## ⌨️ Git Commands

| Git command | What it do |
|-------------|------------|
|git init                                  |Will start git|
|git status                                |Will show current status of git|
|git remote add origin + URL               |Will link a local repository and cloud repository|
|git add . || gut add fileName             |Will add the current files to the commit|
|git commit --amend -m "Text about commit" |Will commit (send to the cloud repository linked) our lastest changes. (--amend will put a prhase in out commit)|
|git commit -m "Text"                      |Will do a commit with generic message|
|rm -rf .git                               |Will delete a git repository|
|git reset --soft hashLastCommit           |Will return posteriors files from the hash we passed|
|git push (-u origin main)                 |Will send the commit to the cloud repositore|
|git pull                                  |Will catch the modified things in cloud repository and put in the local repository|


## 🌳 Branches
- A branch is a rammification of the project. When we want to add new functionalities in the project, we create a new branch before to put in the Main branch
- If exist only a branch, like the Main branch, can be cause confision inside the project. So, we can create a branch "Test" to put new functionalities of the project.
- The commit will go to the branch Test, and after, if approved, will go to the branch Main.
### git checkout -b nameBranch - We create a new branch nameBranch and point to it.
### git checkout nameBranch - Go to the branch nameBranch.
### git branch -v - Show the lastest commit in the branchs
### git merge nameBranch - Combine the actual branch with the nameBranch branch
- After this, all files of nameBranch will appear in the actualBranch
### git branch -d nameBranch - Delete nameBranch.

## Conflicts
- Sometimes the will exist merge conflicts, where to devs will send files about the same location.

