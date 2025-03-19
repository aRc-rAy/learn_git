## show

```git
      git show HEAD
```

### go to parent

```git
      git show HEAD~2
```

```git
      git show HEAD^^
```

### log

```git
      git log --oneline
```

```git
      git log --oneline --graph --all --decorate
```

```git
      git log -p
```

### Branch

```git
      git  checkout -b add_feature
```

### reset

```git
      git reset --soft <tree-ish>
```

```git
      git reset --hard <tree-ish>
```

### stash

```git
      git stash save "stash begins here"
```

```git
      git stash list
```

```git
      git stash show -p stash@{0}
```

```git
      git stash apply stash@{0}
```

```git
      git stash drop stash@{0}
```
