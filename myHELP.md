# How to use Git and GitHub.
[Command sheet ref.](https://qiita.com/okamu_/items/d52a6900311ad9073628)
## Create local repository.
At your working directory.
```
$ git init
```

## Add and Commit
If you alresdy have some files what you want to upload, let's do add and commit to local repository.
```
$ git add <file-name>
$ git commit -m "<prefix>: <some comments>"
```
Please refer to DEVELOPERS.md about prefix.

## Push to remote repository
### First time to push
```
$ git remote add origin <remote repository URL>
```
### Not first time
```
$ git push origin master
```
### Not recommended technic
When we push to remote repository, we got some issues sometimes.
Then, we can't push well to remote repository.
There is technic to force pushing to remote repository.
```
$ git push -f origin master
```
* It works anytime. But update all forcibly. Need to pay attention. Especially, you work with other coraborators.

## Make branch

## Pull and Merge
