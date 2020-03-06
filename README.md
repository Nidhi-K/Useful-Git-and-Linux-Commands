# Useful-Git-and-Linux-Commands
A quick reference guide to useful commands in linux terminal and git version control

## Useful Linux commands

* Search for word in directory: `grep -rn “word”`. `-r` for recursive, `-n` for line numbers

* Create tar archive file: `tar -cvf <NameofArchiveFile>.tar /Directory/to/archive`
* Untar files in current directory: `tar -xvf <NameofArchiveFile>.tar` 
* Untar files in specific directory:`tar -xvf <NameofArchiveFile>.tar -C /Directory/to/untar`
* Find a file in a directory: `find -name *<part_of_filename>*`

## Useful Git commands

* Remove untracked files and folders: `git clean -fd`

* View unpushed changes: `git log origin/master..HEAD`

* Ask git to ignore files (like training images): add the file or folder to `.gitignore` in the root directory of your git repo.

* Ignore files that have already been tracked but are now in `.gitignore`: `git rm --cached <filename>` or `git rm -r --cached <foldername>`

## Lines to add in vimrc for ease of use

* redefine tab to 4 spaces:
```
set tabstop=4
set softtabstop=0 noexpandtab
set shiftwidth=4
set tabstop=8 softtabstop=0 expandtab shiftwidth=4 smarttab
```
* enable syntax highlighting: `syntax on`

* view line numbers: `set nu`
