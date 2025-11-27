# GitHub Operation Guide - Anti-Dementia Manual
![GitHub release](https://img.shields.io/github/v/release/MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual?style=for-the-badge)
![Downloads](https://img.shields.io/github/downloads/MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual/total?style=for-the-badge)
![License](https://img.shields.io/github/license/MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual?style=for-the-badge)
## Create a new repository on GitHub
- Open the GitHub official website and log in to your account.
- Click the + sign in the upper right corner and select "New repository".
- Fill in the name of the warehouse.
- Do not check "Initialize this repository with a README" (because we will initialize it locally).
- Click "Create repository".

## Configure Git locally (Settings required for the first use)

```powershell
git config --global user.name "你的 GitHub 用户名"
git config --global user.email "你的 GitHub 注册邮箱"
```
## Create a project locally and push it to GitHub
Create and enter the project directory
```powershell
mkdir my-first-repo
cd my-first-repo
```
Initialize the Git repository
```powershell
git init
```
Create a file (such as a README)
```powershell
echo "# My First Repo" > README.md
```
Add files and submit
```powershell
git add README.md
git commit -m "Initial commit"
```

## Associate the remote repository
Go back to the repository page you just created on GitHub and copy its HTTPS address
```powershell
git remote add origin https://github.com/你的用户名/my-first-repo.git
```

## Push to GitHub
The following three commands are all acceptable
```powershell
git push
git push -u origin main
git push -u origin master
```

## Daily push and maintenance of git versions
Check which files have been modified
```powershell
git status
```
Add all the modified files
```powershell
git add .
```
Or only add a specific file (for example notes.md)
```powershell
git add notes.md
```
Submit changes
```powershell
git commit -m "v1.0"
```
Push to GitHub
```powershell
git push
```

## Stars
[![Star History Chart](https://api.star-history.com/svg?repos=MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual&type=Date&theme=dark)](https://star-history.com/#MKCorleonE/GitHub-Operation-Guide---Anti-Dementia-Manual&Date)
