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

set the default branch to ***main*** (Because of an update of default branch from Master to main on Github)  
```bash
git config --global init.defaultBranch main
```

Add all files to local git
```bash
git add .
```
  
Add comments for records
```bash
git commit -m "Initial Commit"
```

Add remote Github, the repository created in the first step
```bash
git remote add origin git@github.com:[This is your personal git SSH path]
```

```bash
git push origin main
```
