## Initialize Git repo command
``` 
git init
```
## get the repo status
```
git status
```
## Add a file/dir to the repo
``` 
git add <file|dir>
```
## Committing from staging area to the repo
``` 
git commit -m "<commit message>"
```
## How to ignore files/dir to the repo
``` 
create .gitignore file in the root of the repo
```
## Cloning a project
``` 
git clone <URL/to/the/git/file.git>
```
## skipping the staging area
```
git commit -a -m "message"
```
## removing files
```
git rm <file>
```
## removing a file from the staging area only -- retain it on the working dir
```
git rm --cached <file>
```
## moving files
``` 
git mv orig_file new_file
```
## checking commit history
```
git log
```
## using the --pretty option
```
git log --pretty=oneline
```
## using --graph option
```
git log --graph
git log --pretty=format:"%h %s" --graph
```
## Undo changes -- changing the last commit
```
git commit --amend
git commit -m 'initial commit'
git add add_file
git commit --amend
```
## unstaging an staged file
```
git reset HEAD <file>
```
## adding remote repositories
```
git remote add <alias> git://github.com/to/my/file.git
git remote -v
```
## fetching updates from the remote master
```
git fetch <alias>
```
## if you cloned a repo and want to fetch updates from the master
```
git fetch origin
```
## listing your tags
```
git tag
```
## create  an annotated tags
```
git tag -a v1.1 -m 'my version 1.1'
```
## sharing tags
```
git push origin <tagname>
```
## git aliases
```
git config --global alias.co checkout
git config --global alias.br branch
git config --global alias.ci commit
git config --global alias.st status
git config --global alias.sh show
git config --global alias.lg log
```

