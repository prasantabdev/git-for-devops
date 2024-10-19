
# Git Commands

## 1. Setting Up a Repository
mkdir git_for_devops              # Create a directory
cd git_for_devops/                # Navigate into the directory
git init                          # Initialize a new Git repository
pwd                               # Print working directory

---

## 2. Configuring User Information
git config --global user.name "prasantbdev"          # Set global username
git config --global user.email "prasantadev14@gmail.com"  # Set global email

---

## 3. Creating and Managing Files
vim hello.txt                     # Create/edit 'hello.txt' using Vim
touch nibba.txt                   # Create 'nibba.txt'
touch nibbi.txt                   # Create 'nibbi.txt'
rm hello.txt                      # Remove 'hello.txt'

---

## 4. Viewing Files and Directories
ls -a                             # List all files, including hidden ones
ls -l                             # List files with detailed information

---

## 5. Staging and Unstaging Changes
git add nibbi.txt                 # Add 'nibbi.txt' to the staging area
git add nibba.txt                 # Add 'nibba.txt' to the staging area
git rm --cached nibba.txt         # Unstage 'nibba.txt'
git add nibba.txt                 # Stage 'nibba.txt' again

---

## 6. Committing Changes
git commit -m "adding files"                      # Commit staged changes with a message
git commit -m "changes tracked"                   # Commit another set of changes
git commit -m "Adding changes"                    # Commit new changes
git commit -m "adding nibbu to tracked stage"     # Commit the latest changes

---

## 7. Checking Repository Status
git status                         # Show the current status of the repository

---

## 8. Viewing Commit History
git log                            # View the commit history

---

## 9. Branching and Switching Branches
git branch                         # List branches
git branch -b dev                  # Create a new branch named 'dev'
git checkout -b dev                # Switch to the 'dev' branch
git checkout master                # Switch back to the 'master' branch

---

## 10. Restoring Files
git restore nibbi.txt              # Restore 'nibbi.txt' to the last committed state

---

## 11. Clearing Terminal and Viewing Command History
clear                              # Clear the terminal
history                            # Show command history
