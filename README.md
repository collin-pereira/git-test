# Git basics
    
    commands
        -git init
        -git config -global user.name 'cpereira-cci'
        -git config -global user.email 'collinp26@gmail.com'
        -git status
        -git add . // -git add names.txt
        -git commit -m "chnaged names.txt"
        -made .gitignore file
        Branching
            -git branch newBranch
            -git checkout newBranch
            -git merge newBranch -m "new branch added"
            -git branch -d newBranch // delete a branch
            -git branch -a // show all branches
            -git push -u origin newBranch//push beach to the remote repo
        -git log --online // show all past commits in one line
        Undoing changes
            -checkout commit // going back to a particular previous state
                -git checkout <id>
                -git checkout master // move back to master
            -revert commit // revert one particular commit
                -git revert <id>
            -reset commit
                -git reset <id> --hard
        getting branches from repo to local
            - git branch addition-branch origin/addition_branch
        collaboration on github
