# Git Cheatsheet

## Discard local changes
### Discard local changes, but save for possible re-use
```bash
git stash
git stash -u
```
### Discard local changes (permanently) for specifica files
```bash
git checkout -- <file>
```

### Discard all local changes (permanently)
```bash
git reset --hard
```
