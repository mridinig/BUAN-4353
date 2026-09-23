# BUAN-4353
Project 1

Don't want to edit main directly, main is a master copy to revert back to incase errors come up

Pulling changes
    git pull
    or
    git fetch //to check what you are going to merge
    git merge


To switch from branch to main
    git switch <branch-name>


To update branch with main
    git switch <branch-name>
    git pull origin main
    git add.
    git commit -m ""
    git push


Updating main with current changes in branch/personal workspace
    git switch main
    git pull origin main
    git merge your-branch-name
    git push origin name


To upload changes to GITHUB:
    git add .
    git commit -m "Your descriptive commit message"
    git push (for the branch you are on, check bottom left corner) 
