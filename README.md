#Git how-to & gloassary of commands

Cheatsheet Glossary 
git clone [http address or hhs] -   will clone a copy to your local machine of the repo

git status-  shows the status of the files and any modified or added files and shows what branch is updated

git add .-   add all files/ new update to the file to the repo only needs to be done once 

git add file name i.e. newFile.js-  will only add file/ new update from that file

git commit -m "add in a comment about what? and why? was chnaged/updated" -     save changes into git

git commit -am "add in a comment about what? and why? was chnaged/updated" -    save changes into git and also adds as well

git push-   push your changes to your remote repo 

git push origin master-     will push your chnages to your master branch with your remote repo

git pull-   pull chnages down from the remote repo to your local machine

git init- will create a new repo from the terminal without setting up within github to begin with

git remote add origin [http or hhs]-    will connect your new repo to github, make sure to create a new repo on github and use the http or hhs to connect it correctly.

git remote -v   -will show any remote repo that have been connected to the new repo

git branch- will show what branches are wihtin the rep, * will show which branch you are in  

git checkout- use to switch between branches i.e. for mmaster to feature/ruthBranch

git checkout -b [what you are calling the branch, normal format is feature/ruth or what your working on] -  

git diff -  what chnages have been made, it compares to versions of the code i.e. master version compared to the branch version. 

git push --set-upstream origin  -i.e. The current branch feature/ruthBranch has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin feature/ruthBranch

git branch -d branch name   - you can use this to dleete branches once they have been merge into the master branch, its uncommon to use the same branch more than once. Confirm this is standard wihtin the team before doing!!!

git reset --hard    - will undo all LOCAL chnages


How-To's 
    Setup commits and add 
        Process
        
Creating a new repo
    Process

Setting up new files/changes to the repo 
    Process

Branching- creating new branches
    Process

sharing a feature branch with local commits
    Process
        git checkout feature/ projectName
        git pull                #Get the latest version from DevOps or github
        git checkout branchName #Name of the branch to work on 

        create/update code 

        git add . or git add fileName 
        git commit -m "what? why? reasons for chnages make this relevant and useful- do not use 'my chnages' or 'test fixed'"

        git checkout feature/repoName 
        git pull #Get the latest chnages from Team Members
        git checkout teamMember branch #! Apply Team chnages BEFORE yours, i.e. Original + Team + Yours!!!
                                    #Any problems/ conflicts will occur here
        
        git checkout feature/repo branch
        git merge teamMeber branch #Merge YOUR changes onto the main feature branch- no risk 
        git push


