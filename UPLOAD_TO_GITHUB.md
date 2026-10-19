# How to Upload MODIChat Android to GitHub

Follow these steps to upload this project to your GitHub account.

## Step 1: Create a New Repository on GitHub
1. Go to [github.com/new](https://github.com/new).
2. Repository name: `modichat-android`
3. Set it to **Public** or **Private** based on your preference.
4. **Do NOT** initialize with a README, license, or .gitignore (we already have these).
5. Click **Create repository**.

## Step 2: Upload the Code via Terminal
Open your terminal (on your Mac), navigate to the project folder, and run these commands one by one:

```bash
# 1. Navigate to the project folder
cd /Users/ag700/Downloads/RE/modichat-android

# 2. Initialize the git repository
git init

# 3. Add all files to the staging area
git add .

# 4. Commit the changes
git commit -m "Initial commit: MODIChat Android replication"

# 5. Rename the branch to main
git branch -M main

# 6. Link the local repo to your GitHub repo
# Replace 'kinkor7' with your actual username if different
git remote add origin https://github.com/kinkor7/modichat-android.git

# 7. Push the code to GitHub
git push -u origin main
```

## Troubleshooting
- **Authentication Error**: If GitHub asks for a password, you must use a **Personal Access Token (PAT)** instead of your account password.
- **Permission Denied**: Ensure you are logged into the correct GitHub account in your terminal.
