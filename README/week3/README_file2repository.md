#Adding a file to a repository from the command line

1.Stage the file for commit to your local repository.

```{sh}
git add <file name>
```
####To unstage a file

```{sh} 
git reset HEAD <file name>
```

2.Commit the tracked changes and prepar them to be pushed to a remote repository.

```{sh}
git commit –m ‘comments’
```

3.Push the changes in your local repository to GitHub.

```{sh}
git push origin master
```

