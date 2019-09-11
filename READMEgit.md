# README file for Git commands

## Definitions of Git and GitHub

### Git

Git is a distributed version-control system for tracking changes in source code during software development. It is designed for coordinating work among programmers, but it can be used to track changes in any set of files.

### GitHub

GitHub is an American company that provides hosting for software development version control using Git.

## Main Git and GitHub commands

### git init

Create a new local repository

### git status

Lists the files you've changed and those you still need to add or commit.

### rm – rf .git

Removes the master from the directory.

### git log

Show a log of the commits done and the CommitId of the commits. This is the leading characters of the changeset ID, up to 10, but must be unique.

### git add . or <file>

Add one or more files to staging.

### git commit -m <"message">

Commit changes to head (but not yet to the remote repository)

### git diff

View all the merge conflicts, shows what lines are added.

### git checkout (code)

Undo local changes. If you mess up, you can replace the changes in your working tree with the last content in head.

### git remote add origin <remote repository URL>

Connect to a remote repository. If you haven't connected your local repository to a remote server, add the server to be able to push to it.

### git remote -v

List all currently configured remote repositories.

### git push origin master

Push the branch to your remote repository, so others can use it.

### git remote remove origin

Removes repository.

### git commit

Opens VIM editor.

## Gitignore files

Gitignore tells Git to explicitly ignore files. They are tracked in a special file called .gitignore that is checked at the root of your repository. There is no explicit git ignore command so the .gitignore file must be edited and commited by hand when you have news you wish to ignore.
