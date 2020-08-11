# CHEAT SHEETS FOR ME #

> ## GIT CHEATS ##
>
>> **For information within your git**
>>> git log = *history of your commits*</br>
>>> git status = *status of the current repository*</br>
>>
>> **For working in the server repository**
>>> git clone "<url>" #insert the url of git repository to take every code in it
    git reset --hard <commit> #reverts to the commit
    git reset --hard origin/master #reverts to the origin/master
    git branch #w/o name list all branches
    git branch <name> #create new branch with defined name
    git checkout <name> #change from one branch to another branch
    git merge #separate branches and combine them together

For changing the actual file
    git add "<filename>" #add the file that was created to be committed
    git commit -m "message" #commits to the master and take 1 args
    git commit <filename> -m "<message>" #adding an specific filename into commit, without "git adding it"
    git push #pushes all of the commits to the server
    git pull #pull any changes from the main repository to the working files

## PYTHON CHEATS

    python -m venv venv #create a virtual environment called venv
