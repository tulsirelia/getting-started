# getting-started
First repo to learn about different commands of Github and to make it handy.

# to get the repo in our local system,
copy the repo's http link,
git clone <link>

# basic commands
git status
git --help
pwd, cd, ls, rm

# adding new files to let it track and updating unmodified files
after making new files and making changes in unmodified files, we need to add them only then we can commit

git add . (will add all the new files and update all the existing filesz) or git add <file name>

# to commit the changes 
after doing all the changes in the unmodified files, these files lie under the category of "modified files"
To make them staged, we need to commit:

 git commit -m "any message"
 git commit -am "when only modified files are there, need not to use git add"

# to add them at their final destination i.e. at our github account
after commiting changes, our files are "staged files"
now we need to make them "unmodified files"

git push origin main

# to push local project to gitHub account
"git init" is the command - used to create a new git repo

git remote add origin <-link->

git remote -v (to verify remote)

git branch (to check branch)

git branch -M main (to rename branch)

git push origin name

(git push -u origin main)(u: upstream),
from next time we can only type "git push" as we had already settled up the upstream


