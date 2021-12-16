# Git Katas Assignment

The task is to go to this repository [git_katas](https://github.com/eficode-academy/git-katas/blob/master/amend/README.md) and then perform the first 19 katas. 

## My practice reordering the commits
```

git add r2.txt
git commit -m "add r2"
git add r1.txt
git commit -m "add r1"
git rebase -i HEAD~2

```
Then I reordered the commits. After that I perfromed

```
git reset --hard HEAD~2
```

to move the HEAD back to the `Add README` commit
