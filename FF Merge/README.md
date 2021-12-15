Q Create a (feature)branch called `feature/uppercase` (yes, feature/uppercase is a perfectly legal branch name, and a common convention).

A Done.

Q Switch to this branch

A Done.

Q What is the output of git status?

A Nothing out of ordinary.

Q Edit the `greeting.txt` to contain an uppercase greeting

A Done.

Q Add `greeting.txt` files to staging area and commit

A Done.

Q What is the output of git branch?

A It shows two branches `master` and `feature/uppercase` with the latter being the current branch.

Q What is the output of `git log --oneline --graph --all`

A A graph like representation of git history.

> Remember: you want to pull in the commit on the feature branch into master. The command 'git merge [branch name]' takes one branch as argument from which it takes commits. The commits are applied to the branch pointed to by HEAD (currently checked out branch).

Q Switch to the `master` branch

A Done.

Q Use `cat` to see the contents of the `greetings.txt`

A Done.

Q Diff the branches

A Done. By using 
```
    git diff feature/uppercase master
```

Q Merge the branches

A Done. By using this set of commands.
```
    git checkout master
    git merge feature/uppercase
```

Q Use `cat` to see the contents of the `greetings.txt`

A Done.

Q Delete the uppercase branch

A Done.

