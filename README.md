# Git Commands Guide

## Version Control System (VCS)
Version control is a system that records changes to a file or set of files over time so that you can recall specific versions later.

If you are a developer and want to keep every version of your code/project (which you most certainly would), a Version Control System (VCS) is a very wise tool to use.

## Git Commands for GitHub Compatibility

### **Set Global Username and Email for Git (Locally)**
```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### **Initialize an Empty Git Repository**
```sh
git init
```

### **Clone an Existing Git Repository**
```sh
git clone <repository_url>
```

### **Add Files to Git (Staging)**
- Add a specific file:
  ```sh
  git add <filename>
  ```
- Add all files:
  ```sh
  git add .
  ```

### **Commit Staged Files to Git**
```sh
git commit -m "Your commit message"
```

### **Restore a File from Being Modified to Tracked**
```sh
git restore <filename>
```

### **Show the Status of Your Git Repository**
```sh
git status
```

### **Show the Branches of Your Git Repository**
```sh
git branch
```

### **Checkout to a New Branch**
```sh
git checkout -b <new-branch-name>
```

### **Checkout to an Existing Branch**
```sh
git checkout <branch-name>
```

### **Remove a Branch from Git**
```sh
git branch -d <branch-name>
```

### **Show Remote Origin URL**
```sh
git remote -v
```

### **Add Remote Origin URL**
```sh
git remote add origin <repository_url>
```

### **Remove Remote Origin URL**
```sh
git remote remove origin
```

### **Fetch All Remote Branches**
```sh
git fetch
```

### **Push Your Local Changes to Remote Branch**
```sh
git push origin <branch-name>
```

### **Pull Your Remote Changes to Local Branch**
```sh
git pull origin <branch-name>
```

### **Check Git Commits and Logs**
```sh
git log
```

---
This guide serves as a reference for essential Git commands. Happy coding! 🚀

