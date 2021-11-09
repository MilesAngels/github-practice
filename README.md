## GIT CHEATSHEET

# Initialize empty repositpry
git init

# Establish the connection between local and remote GIT repository
git remote add origin https://github,com/username/repository-name.git

# Show connected repository
git remote show origin

# Disconnect the connection between local and remote GIT repository
git remote remove origin

# Switching between branches
git checkout branch

# Creating new branches from current branch
git checkout -b new-branch-name

# List out local branches
git branch

# Checking the status of a current branch
git status

# Add all uncommited changes in the current directory
git add -A OR git add .

# Commiting your local changes
git commit -m "your message goes here"

# Pushin your committed changes
git push origin branch-name

Work