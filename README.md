# Neontribe Safeguarding

## Make sure I'm up to date

    git pull origin BRANCHNAME

or

    git pull origin Untangled

## Switch to a different branch

    git checkout BRANCHNAMER

## Create a new branch

From the branch you want to base the new one from

    git checkout -b BRANCHNAME

## List branches

    git branch

## See what has changed

    git status

## Add a new file

To the local version

    git add FILENAME

or to add all new files.

    git add -A 

## Update changes

Into the local version, this will pop out an editor to add the message

    git commit -a 

or to include the message in the command

    git commit -a -m 'This will be the commit message'

## Update the branch on github

    git push origin BRANCHNAME
