### Git Command For Reference

# To initialize a git
```
$ git init
```

# Add a file into staging area
- To add a single file
```
$ git add filename
```
- To add multiple files
```
$ git add .
```

# Commit
```
$ git commit -m "Add a message here with the quotation mark"
```

# Check status and commit history
- Check status
```
$ git status
```
- Check commit history
```
$ git log --oneline
```

# View a commit
```
$ git checkout commit-id
```

# Revert (Undo a commit - Safe)
```
$ git revert commit-id
```
When a window pop up, press ```shift``` + ```;``` then type in ```wq``` and hit ```ENTER```.

# Reset (Reset code to a particular commit)
- If you want to give yourself some room to rethink about it, use this command:

```
$ git reset commit-id
```
- If you are 200% sure that you want to reset the code to a particular commit, and delete all the commit after it:
```
$ git reset commit-id --hard
```

### Branching
- Create a new branch
```
$ git branch brance-name
```
- Switch to a branch
```
$ git checkout branch-name
```
- Create and switch to new branch
```
$ git checkout -b new-branch-name
```
- Delete merged branch
```
$ git branch -d branch-name
```
- Delete unmerged branch
```
$ git branch -D branch-name
```
- To show all branches
```
$ git branch -a
```
- To merge branches
```
$ git merge branch-name
```
