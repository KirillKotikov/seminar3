# Instruction how to use Git

![Git logo](Git-Logo-2Color.png)

## Creating repository

Enter next command for create local repository

    git init

## Status control

Enter next command for geting status

    git status

## Adding files for tracking

Enter next command for adding file into tracking

    git add file_name

## Saving this stage in local repository

    git commit -m "Your message"

Message need for information about changes in this stage

## Show history of commits

    git log

For hashes and names in one line:

    git log --oneline

## Traveling on history of commits

    git checkout commits_hash

comits_hash is may be first four number or branch name

## Showing changes

    git diff

This will show the changes in the file

If you want to compare another commits:

    git diff first_commit_hash second_commit_hash
    

## Branches

### Branch list:

### Create branch