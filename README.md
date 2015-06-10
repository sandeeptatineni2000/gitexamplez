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
