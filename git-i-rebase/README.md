# __Git Interactive Rebase__

# __Project Tasks__


_Interactive Rebase (Squash)_
---
1. Creat a branch with the name `feat/rebase` 

    - Create a file blog.txt with the commit message: 
        
        "A: First blog post" 

    - Add text to the file and commit with message:
    
        "B: Append Fitx typo in blog post" 

    - Add more text to the file and commit with the message: 
    
        "C: Append Updated blog post formatting"

2. Run an interactive rebase over the last 3 commits: 
 use the command `git rebase -i HEAD~3`
    
3. Squash the commits starting with "B:. . ." and "C:. . ."  with the commit "A: First blog post."

    - For the suqashed commit, use the commit message  
        
        "D: Add first blog post with formatting"

_Interactive Rebase (Reword & Reorder)_
---

1. On the feat/rebase branch, add information to the blog.txt file and make 3 commits with commit message in this order:
    -  "A: Add Contact info"
    -  "B: Add About page"
    -  "C: Add Service list"

2. Enter interactive rebase mode using command:
`git rebase -i HEAD~3`

3. Reorder commits so that they are in the below order:
     
     - "C: Add Service list"
     - "A: Add Contact info"
     - "B: Add About page"

4. Reword the lastest commit with message:
    - "C: Add Service list section (reword)"


_Split a Commit (Advanced Interactive Rebase)_
---
1. On feat/rebase branch, create two files:

    - roles.txt 
    - team.txt

    Commit both files with commit message: "Add team information"

2. Split both commits into two separate commits using interactive rebase.

    Each file should be commited with commit message as shown below:

    | file name  | commit message  |
    | ---        | ---             |
    | team.txt | Add team members         |
    | role.txt | Define team member roles |


3. Continue the rebase so history has two neat commits instead of one.

---
