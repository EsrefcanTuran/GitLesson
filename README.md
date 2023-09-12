# Ctrl+ Future Training: Github Fundamentals  
## Training to introduce the cohorts how to push from a local environment to GitHub.  
## Common Linux Commands  
- Create a directory: **mkdir** name of the directory  
- Change directory: **cd** name of the directory (This commands helps you to move from one directory to another)  
- Create a file: **touch** name of the file (This command helps you to create a file within the directory)  
- List the contents in a directory: **ls**  
- Remove a file: **rm**  file name (This command removes a file)  
- Remove an empty directory: **rmdir**  name of the directory (This command removes an empty directory)  
## Download Git Bash  
- https://git-scm.com/downloads
## Configure Git Bash
- **git config --global user.name "Your name"**  
- **git config --global user.email "Your email"**
## Prepare Your Working Environment
- **mkdir website**
- **cd website**
- **git init**
- **touch index.html**
- **vim index.html** (to add content to the html file)
## Clone Your Repository  
- **git remote add origin (url of your repository)**  -Use HTTPS link
## Push from your local environment to GitHub  
- **git status** (This helps to check the files on the staging area)  
- **git add index.html** (This adds your files to the staging area)
- **git commit -m "Commit message"** (Commit command helps you to take a snapshot of what you did at that moment of time)
- **git push origin main** (This command pushes the changes to the repository)
