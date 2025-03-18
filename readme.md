## Learn git

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

```git
      git help ls-tree
```

```git
      git ls-tree HEAD
```

### log

```git
      git log -3
```

```git
      git log
```

```git
      git log --online
```

```git
      git log --since=2019-04-12
```

```git
      git log --author="sumit"
```

```git
      git log --grep="initial"
```

```git
      git log -p
```

```git
      git log --stat
```

```git
      git log --format=short
```

```git
      git log --graph
```

```git
      git log --oneline --graph --all --decorate
```

### Branch

```git
      git branch
```

```git
      git branch new_feature
```

```git
      git checkout new_feature
```

```git
      git  checkout -b add_feature
```

```git
      git branch -M del_feature
```

#### compare branches

```git
      git diff master..new_feature
```

#### rename

```git
      git branch -m seo_title
```

#### del branch

```git
      git branch -d branch_to_del
```

### reset

#### soft

```git
      git reset --soft <tree-ish>
```

```git
      git reset --hard <tree-ish>
```

### merge
