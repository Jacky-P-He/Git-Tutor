# Git-Tutor
A guide to help new users get started with git

## 1. Create a git repository on your GitHub Website.
Create the name  
Add a description (optional)  
Set to 'Public' or 'Private'

## 2. Open a terminal on your local desktop
cd to the folder you want to work on  
```bash
cd \[This is your folder path]
```

create git environment  
```bash
git init
```

Add remote Github, the repository created in the first step
```bash
git remote add origin https://github.com/...[This is your personal git HTML path]
```

get origin folder on GitHub, the README file
```bash
git pull origin main
```

set the master branch to ***main*** (Because of an update of default branch from Master to main on Github)  
```bash
git branch -m master main
```

Add all files to local git
```bash
git add .
```
  
Add comments for records
```bash
git commit -m "Initial Commit"
```

```bash
git push --set-upstream origin main
```
