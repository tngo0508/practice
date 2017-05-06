# create a new local repository
    git init   

# connect to a remote repository
    git remote add origin <server>

# list all currently configured remote repos
    git remote -v

# create a new branch and switch to it
    git checkout -b <branchname>

# switch from one branch to another
    git checkout <branchname>

# list all the branches in your repo, and also tell you what branch you're currently in
    git branch

# delete branch
    git branch -d <branchname>

# commit before push (commit changes to head but not yet to the remote repo) 
    git commit -m "commit message"

# commit any files you're added with git add, and also commit any files you're changed since then
    git commit -a

# list the files changed and those you still need to add or commit
    git status

# send changes to the master branch of your remote repository
    git push origin master


# in short,

    mkdir git-repos
    cd repos
    git init
    git remote add origin <https>
    git status
    git commit -m "message"
    git push origin master

