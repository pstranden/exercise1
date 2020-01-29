# exercise1

This is a README file describing all the neat stuff inside this repository.

It's also a good place for instructions:

## Clone the repo

Copy the repository metadata to the current directory and checkout the default branch 'master'.

`git clone`

## Browse the repository content

Find the repository you cloned in file explorer and see what's there (nothing much isn't it?). Then go into the same 
directory and see what does the metadata tell you:

`cd exercise1`

`git log`

`git status`

You can also try graphical tool to see the commits:

`gitk`

## Branches

Create a feature branch (based on branch you're on - propably master)

`git checkout -b <your-very-own-feature-branch>`

check you see your feature branch listed:

`git branch -a`

but wait a second: the feature branch "origin/add_participants" already exists. Checkout the contents:

`git checkout add_participants`

## Working

Make changes to repository content (edit files, create a new file). You can make changes anyway you like.

Add your name into the file "participants.txt" (keep the names ordered alphabetically). You can open the file for editing for example in file explorer.

Let's see what you have been doing:

`git status`

`git diff`

When you're done editing: prepare the staging area for a commit

`git add <file1 file2 file3>`

Create a commit

`git commit -m "something describing what have you been up to, preferably starting with a ticket/issue number for the task"`

Publish your work on remote repository (server)

`git push`

## Conflict resolving

Problems? hmmm... did you check if anyone else had any changes?

`git pull`

Resolve any conflicts you might have before retrying

`git status` (tells you what files have conflicts)

edit <file1> (resolve the conflict manually)

`git add <file1>` (tell the git that <file1> is now fixed)

`git status` (instructs how to proceed)

`git commit` (finalize merging)

`git status` (does everything look ok?)

`git push`

Did you still have conflicts? try to be quicker. try a command:

`git pull --rebase`

If you still have conflicts resolve those.

Publish your work

`git push`

