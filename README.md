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

## Tags

I created 2 tags names `squash` and `README` for 2 different commits.

The tag `squash` for `HEAD` commit
```
git tag "squash"
```

The tag `README` for "Add README" commit by replacing the command
```
git tag "README" <commit-hash>
```
with
```
git tag "README" e5a8f04
```