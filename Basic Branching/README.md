Q Use `git branch` to see the two branches that are relevant for this exercise

A Done

Q What branch are you on?

A Master

Q Use `git branch mybranch` to create a new branch called `mybranch`

A Done

Q Use `git branch` again to see the new branch created.

A Done

Q Use `git switch mybranch` to switch to your new branch.

A Done

Q How does the output from git status change when you switch between the master and the new branch that you have created?

A No change for now.

Q How does the workspace change when you change between the two branches?

A No change for now.

Q Make sure you are on your mybranch branch before you continue.

A Done.

Q Create a file called file1.txt with your name.

A Done

Q Add the file and commit with this change.

A Done.

Q Use git log --oneline --graph to see your branch pointing to the new commit.

A Done

Q Switch back to the branch called master.

A Done

Q Use git log --oneline --graph and notice how the commit you made on the mybranch branch is missing on the master branch.

A Done

Q Make a new file called file2.txt and commit that file.

A Done

Q Use git log --oneline --graph --all to see your branch pointing to the new commit, and that the two branches now have different commits on them.

A Done.

Q Switch to your branch mybranch.

A Done.

Q What happened to your working directory? Can you see your file2.txt?

A Workspace changes and file2.txt was removed from working directory.

Q Use git diff mybranch master to see the difference between the two branches.

A Done.