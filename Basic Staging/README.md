Q What's the content of `file.txt`?
A 1

Q Overwrite the content in `file.txt: echo 2 > file.txt` to change the state of your file in the working directory (or sc `file.txt` '2' in PowerShell)
A Done

Q What does `git diff` tell you?
A Nothing

Q What does `git diff --staged` tell you? why is this blank?
A Nothing

Q Run git add `file.txt` to stage your changes from the working directory.
A Done

Q What does `git diff` tell you?
A Nothing

Q What does `git diff --staged` tell you?
A it printed out some info related to changes that i made in `file.txt`

Q Overwrite the content in `file.txt: echo 3 > file.txt` to change the state of your file in the working directory (or sc `file.txt` '3' in PowerShell).
A Done

Q What does `git diff` tell you?
A It displayed that that i deleted 2 and inserted 3. (my modifications to file, insertion and deletion)

Q What does `git diff --staged` tell you?
A It displayed the same info as before.

Q Explain what is happening
A I dont understand clearly. I have a vague idea.

Q Run git status and observe that `file.txt` are present twice in the output.
A Yes there is. And I know why exactly is that !!

Q Run git `restore --staged file.txt` to unstage the change
A Was facing issue bacuase of no commits. It's resolved now !!

Q What does `git status` tell you now?
A It has removed my file from staging area (index).

Q Stage the change and make a commit
A Done

Q What does the log look like?
A It shows my commit.

Q Overwrite the content in `file.txt: echo 4 > file.txt` (or sc `file.txt` '4' in PowerShell)
A Done

Q What is the content of `file.txt`?
A 4

Q What does `git status` tell us?
A It says file.txt was modified but is not staged yet.

Q Run `git restore` `file.txt`
A Done

Q What is the content of `file.txt`?
A It restored the file to original state.

Q What does `git status` tell us?
A Nothing.
