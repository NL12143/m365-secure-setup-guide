
# Clone your repo
git clone https://github.com/yourusername/yourrepo.git
cd your-repo

# Create a new branch with no history
git checkout --orphan clean-main

# Add all files
git add .

# Commit the current state
git commit -m "Clean start with final version"

# Delete old branch
git branch -D main

# Rename new branch to main
git branch -m main

# Force push to GitHub
git push --force origin main

-------------------------------------

git rebase -i HEAD~N
