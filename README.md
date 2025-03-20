# Installing and Setting Up Git for Version Control

## TechnoHacks Solutions Pvt. Ltd. Internship Program 2025

### Overview
This guide provides step-by-step instructions on installing and setting up Git for version control. Git is a distributed version control system that allows developers to track changes in their code and collaborate efficiently.

---

## Prerequisites
Before installing Git, ensure that you have:
- A system running **Windows, macOS, or Linux**
- An active **internet connection**
- **Basic command-line knowledge** (recommended)

---

## Installation Steps
### **Linux (Ubuntu/Debian)**
1. Open a terminal and run:
   ```sh
   sudo apt update
   sudo apt install git -y
   ```
2. Verify the installation:
   ```sh
   git --version
   ```

### **Linux (Fedora/RHEL)**
1. Open a terminal and run:
   ```sh
   sudo dnf install git -y
   ```
2. Verify the installation:
   ```sh
   git --version
   ```

---

## Initial Configuration
After installing Git, configure your user identity:
```sh
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```
To check the configuration, run:
```sh
git config --list
```

---

## Creating a New Repository
To initialize a new Git repository:
```sh
mkdir my-project
cd my-project
git init
```
To check the repository status:
```sh
git status
```

---

## Cloning an Existing Repository
To clone a repository from GitHub or another source:
```sh
git clone https://github.com/username/repository.git
```

---

## Making Your First Commit
1. Create a new file:
   ```sh
   echo "# My Project" > README.md
   ```
2. Add the file to the staging area:
   ```sh
   git add README.md
   ```
3. Commit the file:
   ```sh
   git commit -m "Initial commit"
   ```
4. Push changes to a remote repository:
   ```sh
   git push origin main
   ```

---

## Branching and Merging
- Create a new branch:
  ```sh
  git branch feature-branch
  git checkout feature-branch
  ```
- Merge a branch:
  ```sh
  git checkout main
  git merge feature-branch
  ```

---

## Conclusion
You have successfully installed and set up Git for version control. This guide provides the foundation for working with Git during the **TechnoHacks Solutions Pvt. Ltd. Internship Program 2025**.


