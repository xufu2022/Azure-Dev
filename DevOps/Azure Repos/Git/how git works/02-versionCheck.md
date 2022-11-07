# Version Check

## internals of Git

**“Porcelain” Commands**
```
git add
git commit
git push
git pull
git branch
git switch
git merge
git rebase
```

**“Plumbing” Commands**
```
git cat-file
git hash-object
git count-objects
…
```

### Git Is

…a Distributed Revision Control System
…a Revision Control System
…a Stupid Content Tracker
…a Persistent Map

### Values and Keys

Any sequence of bytes -----> SHA1 hash

```
“Apple Pie” ----> 23991897e13e47ed0adb91a0082c31c82fe0cbe5
```

Every object in Git has its own SHA1.
So, what if they collide?
SHA1s are unique in the universe.

### Git Objects

Blobs 
Trees 
Commits 
Annotated Tags

