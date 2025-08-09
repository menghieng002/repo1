Start Git Local Repository
    Config User
    > git config --global user.name 'Menghieng Sorn'
    > git config --global user.main 'menghieng002@gmail.com'
    Working Directory
        > mkdir git-demo
        > git init
        > touch file1.txt
        > git status
    Staging Area
        > git add .
        > git status
        > git ls-files
    Local Repository
    > git commit -m "message"

Check Commit History
    > git log
    > git log --oneline
    > git show 40856ad

Modify File
    git commit -am 'modify message'
Check File Modify Unstage
    > git diff file2.txt
    > git diff --staged filename.txt

Delete File Working Directory
    > git rm file3.txt
Delete File Only Local Repository
    > git rm --cache file2.txt
    > Create .gitignor
Revert File (Undo or Redo)
    > git revert 40ad076

Reset File 
    Hard
        > git reset --hard HEAD~2
   
Branching
    > git branch
    create new branch copy from main
        > git branch b1 main
    Swich branch
        > git checkout b1
    Delete branch 
        > git branch -d b1
        > git push origin -d b1
Merging file
    > git merge b1 main
Stash file
    > git stash
    >git stash list
    > git show stash@{0}
    > git stash apply stash@{0}
Unstash file
    > git stash pop stash@{0}
Clear stash
    > git stash clear
Spacific stash 
    > stash@{0}
Rebase
> 

Remote Repo
    > git remote add origin https://github.com/menghieng002/repo1.git
    > git remote -v
Clone Repo
    > git init
    > git clone https://github.com/menghieng002/repo1.git
Push To Repo
    > git push origin main
Check update on Repo
    > git fetch origin main
Pull to Repo
    > git pull origin main
    
    
