# BUAN-4353
Project 1

Don't want to edit main directly, main is a master copy to revert back to incase errors come up

To switch from branch to main: git switch <branch-name>

    To update branch with main
    git switch <branch-name>
    git pull origin main


Updating main with current changes in personal workspace/branch
    git switch main
    git pull origin main
    git merge your-branch-name
    git push origin name


To update file with most recent verison:
    git fetch
    git merge

    OR 

    git pull / git pull origin main



To upload changes to repository:
    git add .
    git commit -m "Your descriptive commit message"
    git push (for the branch you are on, check bottom left corner) 
    then git push origin name if you want to update main