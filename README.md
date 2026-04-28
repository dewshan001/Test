# Initialize the local folder as a Git repository
git init

# Add all files in the current directory to the staging area
git add .

# Commit the files with a descriptive message
git commit -m "Initial commit"

# Create a main branch (standard naming convention)
git branch -M main

# Link your local repo to the remote server
# Replace <URL> with your actual repository link
git remote add origin <URL>

# Push the code to the 'main' branch of 'origin'
git push -u origin main

<img width="1083" height="452" alt="image" src="https://github.com/user-attachments/assets/83edbe0e-ed37-4c8a-b5ac-da5d972a377a" />

# Rename the default branch to 'main'
git branch -M main

# Link your local repository to the remote server
# Replace <REPO_URL> with your actual repository link
git remote add origin <REPO_URL>

# Push to the remote 'main' branch
git push -u origin main

<img width="1158" height="422" alt="image" src="https://github.com/user-attachments/assets/dc3e7043-2b2a-4270-bedf-0360deef4cb1" />

<img width="856" height="191" alt="image" src="https://github.com/user-attachments/assets/5c5c84e3-6271-4075-98c2-2953b4d069ca" />


#change repo
# First, check the current repository your project is linked to
git remote -v

# Change the repository URL to the new one
# Replace <NEW_REPO_URL> with the new GitHub repository link
git remote set-url origin <NEW_REPO_URL>

# Verify that the URL has been successfully changed
git remote -v

#change branch
# List all your local branches to see your options
# The branch you are currently on will have an asterisk (*) next to it
git branch

# Switch to an existing branch
# Replace <branch_name> with the name of the branch you want to move to
git switch <branch_name>

<img width="949" height="199" alt="image" src="https://github.com/user-attachments/assets/1c38398e-55d7-4e1c-bc72-4a3981e13f8e" />




