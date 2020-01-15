# exercise1

This is a README file describing all the neat stuff inside this repository.

Here's also a good place for instructions:

# clone the repo
git clone

# browse the content
git log
git status

# create a feature branch (based on branch you're on - propably master)
git checkout -b <your-very-own-feature-branch>
# check you see your feature branch listed:
git branch -a
# but wait a second: the feature branch "add_participants" already exists
git checkout add_participants

# work! (edit files, create a new file)
# Add your name into the file "participants.txt" (keep the names ordered alphabetically)

# let's see what you have been doing
git status
git diff

# when you're ready: prepare the staging area for a commit
git add <file1 file2 file3>

# create a commit
git commit -m "something describing what have you been up to, preferably starting with a ticket/issue number for the task"

# git push
git push

# problems? hmmm... did you check if anyone else had any changes?
git pull

# resolve any conflicts you might have before retrying
(git status; #edit fileA; git add <fileA>; git status)
git push

# still have conflicts? try to be quicker. try a command:
git pull --rebase

# push your changes
git push
# akinrepo
# akinrepo
