Create a Git directory
mkdir intro-to-git
cd intro-to-git
ls
ls -a # see all
git init # notice (master)
touch README.md
git status
git add README.md
git status  
git commit -m "add README.md"
git status
git log
touch test.html
touch hello-world.html
touch README.txt
ls
git add *.html
git commit -m "Add all files with .html"
git log
touch hello.css
touch hello.js
touch foobarbas.html
touch .hidden.txt
ls
ls -a

# Working Directory
- Area where all files and directories and changes are living all the time.

# Staging Area
- Files and directories that we explicityly add to the staging area.

# Git Repository
- Where all our snapshots are stored.

# Adding multiple files of a certain type

# Adding all files in a directory (including hidden)
git add -A
"*" is wild card

# Removing files
git reset HEAD file_name

# Ignoring files












