# Useful-Git-and-Linux-Commands
A quick reference guide to useful commands in linux terminal and git version control

## Useful Linux commands

* Search for word in directory: `grep -rn “word”`. `-r` for recursive, `-n` for line numbers
* Create tar archive file: `tar -cvf <NameofArchiveFile>.tar /Directory/to/archive`
* Untar files in Current Directory: `tar -xvf <NameofArchiveFile>.tar`
* Untar files in specified Directory: `tar -xvf <NameofArchiveFile>.tar -C /Directory/to/untar`

## Useful Git commands

* Remove untracked files and folders: `git clean -fd`

* View unpushed changes: `git log origin/master..HEAD`

* Ask git to ignore files (like training images): add the file or folder to `.gitignore` in the root directory of your git repo.
* Ignore files that have already been tracked but are now in `.gitignore`: `git rm --cached <filename>` or `git rm -r --cached <foldername>`
