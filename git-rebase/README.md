# Git Rebase

## Project Tasks

1. Create a new branch feature/notes from main.

2. Add two commits on feature/notes:
    - First commit: create notes.txt with text  Header section.
    - Second commit: append Header styles to notes.txt.

3. On main, add a commit that creates background.txt with text Background color: blue.

4. Rebase feature/notes on top of main so that notes.txt commits come after the background commit.

5. Create a new branch feature/footer from main.
    
6. Add a commit in feature/footer that appends Footer section to project.txt.
    
7. On main, add a commit that also appends Main body text to project.txt.

8. Rebase feature/footer on top of main.
    - Resolve the conflict in project.txt so both changes appear.
    - Continue the rebase until it finishes.