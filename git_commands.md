# Git Commands for Uploading Project to GitHub

## Step-by-Step Process

1. Update .gitignore to exclude venv:
   - Edit .gitignore to add "venv/" under # Virtual environments

2. Initialize Git (if not already):
   - git init

3. Check Git status:
   - git status

4. Add all files:
   - git add .

5. Commit changes:
   - git commit -m "Initial commit: Add project files and update .gitignore to exclude venv"

6. Create GitHub repository:
   - Go to GitHub.com, create new repository (e.g., mcp-weather-project), public, no README.

7. Add remote:
   - git remote add origin https://github.com/yourusername/mcp-weather-project.git

8. Push to GitHub:
   - git push -u origin main

## Notes
- Ensure GitHub CLI is installed for easier repo creation: gh repo create repo-name --public --source=. --remote=origin --push
- Replace 'yourusername' with your actual GitHub username.
- The venv folder is excluded via .gitignore to prevent uploading virtual environments.
