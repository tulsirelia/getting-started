# getting-started
First repo to learn about different commands of Github and to make it handy.

# to get the repo in our local system,
copy the repo's http link,
git clone <link>

# basic commands
git status
git --help
pwd, cd, ls, rm

# adding new files to let it track
after making new files, we need to add them only then we can commit

git add . (will add all the new files) or git add <file name>

# to commit the changes 
after doing all the changes in the unmodified files, these files lie under the category of "modified files"
To make them staged, we need to commit:

 git commit -m "any message"

# to add them at their final destination i.e. at our github account
after commiting changes, our files are "staged files"
now we need to make them "unmodified files"

git push origin main


