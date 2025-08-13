# Git Commit Messages

Git commit messages helps you Identify what changes were made to your files and folders.

writting good commit messages helps you makes sense of the changes that occur during your projects.

Imbibing best practices from the begining helps prevents you develpoing bad inveterate practices.

## Commit Message Best Practice
One recommended best practice when writing commit messages is to use a template file that contains commit guides you can use in writting your commits.

## Setting up a commit guide
- Create the commit text file using a text editor
![image]() 

    NOTE: Although it is not a requirement, you should save this text file in your home directory. 
    You also don't need to worry about the #. When it is rendered on git hub. the #'s are ignored.

- use the command: `git config --global commit.message` `[file location]` 
This command ensures that anytime you run `git commit` you use the template. 
 
 ## How Repo conflicts and mismatch are avoided

 Here’s the **safety interplay** in one tight summary:

* **Shared history check** → Prevents you from accidentally pushing an unrelated local project to a remote repo.

  * If no common commit ancestry, push is rejected unless you `--force`.

* **Existing `.git` check** → Prevents you from accidentally overwriting an existing local repo when cloning.

  * If `.git` already exists, clone is blocked unless you remove `.git` or clone elsewhere.

**In short:**
Git blocks strangers from merging unless you explicitly bypass the warning.
One guard protects the **remote**, the other protects the **local**.
