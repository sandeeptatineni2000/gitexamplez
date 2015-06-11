# Useful GIT Commands

### Creating a repo online for <b>first time</b>!
``` sh
$ touch README.md
$ git init
$ git add README.md
$ git commit -m "first file commit"
$ git remote add origin https://github.com/sandeeptatineni2000/gitexamplez
$ git push -u origin master
#put in username and password
```


### When adding on to your repository online with changes
``` sh
$ git add README.md or git add .
$ git commit -m "added new commands"
$ git push
#put in username and password
```

### No more username and password input for every push
``` sh
$ git remote set-url origin git@github.com:sandeeptatineni2000/gitexamplez.git
#got using ssh clone url
```

###Deleting a file on remote serer or website when you have deleted it locally
``` sh
$ git add -u
```

<<<<<<< HEAD
=======
### Working together with others
```sh
# fork repo you want to work on
$ git clone https://github.com/saitatineni2000/gitexamplez.git
```
>>>>>>> 68d55da9d2cd1680ed6a70c03ee6b5b9dcd9661d

###Removing a file from online but keep it locally
``` sh
$ git rm -- cached localFileName
# add localFileName to .gitignore file and then commit the changes
```

### Commands for fixing problems

``` sh
#undo multiple commits
$ git reset --hard commitSHA###...=changes staging index and local folde to match online repo commit

# removing 3 commits from online github repo
$ git push -f origin HEAD^^^:branchNameToUndoLast3Pushs
```


###Branch Commands
``` sh
$ git branch 
#list all branches in working folder

$ git branch newBranchName
$ git checkout newBranchName
#switch to branch newBranchName

$ git push origin newBranchName 
# adds new Branch to github

$ git branch -d branchNameToDelete 
#delete branch while you are on different branch
```
