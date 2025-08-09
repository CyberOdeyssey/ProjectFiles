# GIT FOUNDATIONS
This project contains foundational knowledge required for git mastery. 
## Project Tasks
1. Create a project folder and initialize it as a Git repository 
2. [ ] Configure your Git username and email for the project.
3. Create a README file and commit it.
4. Add another file with some content and commit it.
5. Create a remote repository on GitHub with the same name.
6. Connect your local repository to the remote one.
7. Push your local commits to the remote repository.

## Solution 
Create the project folder. You can do this from VS code or from windows explorer.
![image]()

To initialize a folder as a git repo
Navigate to the directory you want git to track, in this case the "git-foundations" directory.
![image]()

 use the command:
`git init` 

![image]()
This folder is now being tracked by git

Add the untracked files to staging and commit to the local repo
using: 
`git add` and  `git commit`



## Challenges Faced and Solutions
I accidentally made the wrong folder a repository
I was supposed to make the ProjectFiles the parent repo
However, I ran `git init` in the child folder. 

To resolve this
- I removed the .git files to stop it from being a git repo
- make the parent directory the git repo 
- added the child folder to the parent repo so that they can be tracked



## Command Summary

