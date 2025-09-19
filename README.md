# insurance

echo "# insurance" >> README.md     # Creates a README.md file with "# insurance" as the first line
git init                            # Initializes a new Git repository in your folder
git add README.md                   # Stages the README.md file
git commit -m "first commit"        # Commits the staged file with a message
git branch -M main                  # Renames the branch to 'main' (GitHub’s default)
git remote add origin https://github.com/vishal259305-sketch/insurance.git  # Links your local repo to GitHub
git push -u origin main             # Pushes your local 'main' branch to GitHub
