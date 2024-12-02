
# Configure your identity
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Check configuration
git config --list
Initialize Repository
bash
Copy code
# Initialize a new Git repository
git init
Add and Commit Changes
bash
Copy code
# Add files to the staging area
git add <file>            # Add a specific file
git add .                 # Add all changes

# Commit changes with a message
git commit -m "Your commit message"
Check Status and History
bash
Copy code
# Check the status of your repository
git status

# View the commit history
git log
Branching
bash
Copy code
# Create a new branch
git branch <branch_name>

# Switch to a branch
git checkout <branch_name>

# Create and switch to a branch
git checkout -b <branch_name>

# Merge a branch into the current branch
git merge <branch_name>
Remote Repositories
bash
Copy code
# Link your local repository to a remote repository
git remote add origin <repository_url>

# Push changes to a remote repository
git push -u origin <branch_name>

# Pull updates from the remote repository
git pull origin <branch_name>
Using GitHub
Creating a Repository on GitHub

Log in to GitHub and click New to create a new repository.
Provide a name and description, and initialize with a README if needed.
Cloning a Repository

bash
Copy code
git clone <repository_url>
Forking a Repository

Use the Fork button on GitHub to create a personal copy of a repository.
Creating a Pull Request

Push changes to a branch.
Navigate to GitHub and create a pull request for the changes.
