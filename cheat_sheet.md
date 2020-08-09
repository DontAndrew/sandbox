# GIT CHEATS

For information within your git
    git log #history of your commits
    git status #status of the current repository
    
For working in the server repository
    git clone "<url>" #insert the url of git repository to take every code in it
    git reset --hard <commit> #reverts to the commit
    git reset --hard origin/master #reverts to the origin/master

For commits, add, push, pull
    git add "<filename>" #add the file that was created to be committed
    git commit -m "message" #commits to the master and take 1 args
    git commit <filename> -m "<message>" #adding an specific filename into commit, without "git adding it"
    git push #pushes all of the commits to the server
    git pull #pull any changes from the main repository to the working files