# Git Command For Reference

For more reference: [Click here](https://www.youtube.com/watch?v=3RjQznt-8kE&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR)

### To initialize a git
> `$ git init`

### Add a file into staging area
> To add a single file
`$ git add filename`

> To add multiple files
`$ git add .`

### Commit
> `$ git commit -m "Add a message here with the quotation mark"`

### Check status and commit history
> Check status
`$ git status`

> Check commit history
`$ git log --oneline`

### View a commit
`$ git checkout commit-id`

### Revert (Undo a commit - Safe)
`$ git revert commit-id`

*When a window pop up, press `SHIFT` + `;` then type in `wq` and hit `ENTER`.*

### Reset (Reset code to a particular commit)
> If you want to give yourself some room to rethink about it, use this command:
```$ git reset commit-id```

> If you are 200% sure that you want to reset the code to a particular commit, and delete all the commit after it:
```$ git reset commit-id --hard```

# Branching
> Create a new branch
`$ git branch brance-name`

> Switch to a branch
`$ git checkout branch-name`

> Create and switch to new branch
`$ git checkout -b new-branch-name`

> Delete merged branch
`$ git branch -d branch-name`

> Delete unmerged branch
`$ git branch -D branch-name`

> To show all branches
`$ git branch -a`

> To merge branches
```
$ git merge branch-name
```

*If there is any conflict during the merging, resolve the conflict then:*
```
$ git add .
$ git commit -m "Message"
```
*When a window pop up, press ```SHIFT``` + ```;``` then type in ```wq``` and hit ```ENTER```.*

# Github
> To push a code onto Github:
`$ git push repo-URL branch-name`
> **OR**
```
$ git remote add origin repo-URL
$ git push origin branch-name
```

> To clone a repository
`$ git clone repo-URL`

>To update your local repo:
`$ git pull origin master`

>To push to Github
`$ git push origin branch-name`
