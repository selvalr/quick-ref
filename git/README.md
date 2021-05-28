# Git Quick Ref

- SCM - It is a Source Code Management tool to manage and track your source code
- Distribution SCM 
- workiong directory -> Staging area -> local repository -> remote repository(github)

### Basic Commands

```bash
git init # Start tracking source code
git status # To see what is the status of git
git add . # start track files[ * and . means all files ]
git add akilan.txt # Track only akilan.txt file
git commit -m "Added linux ref file" # Commit the changes to local repository
git diff $FILENAME # show the difference in the file [ current version vs commited version]
git diff # show the difference of all files [ current version vs commited version]
# Utility
git config --global user.email "selvamanan369@gmail.com" # Tell the git about who is commiting
git config --global user.name "Selva" # Tell the git about who is commiting

# Remote repo config
git remote add origin https://github.com/selvalr/quick-ref.git
git branch -M main
git push -u origin main

# Repeative commands
git status
git add .
git commit -m "added my changes"
git push
```