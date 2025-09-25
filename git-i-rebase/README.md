# Git Interactive Rebase

## Project Tasks
__Interactive Rebase (Squash)__
1. On main, make 3 commits:
    - Create blog.txt → First blog post.
    - Append Fix typo in blog post.
    - Append Updated blog post formatting.

2. Run an interactive rebase over the last 3 commits: `git rebase -i HEAD~3`
    
3. Squash the typo and formatting commits into the first one.
    - Final message → Add first blog post with formatting.

__Interactive Rebase (Reword & Reorder)__

1. On main, make 3 commits in this order:
    - Create contact.txt → Contact info.
    - Create about.txt → About page.
    - Create services.txt → Services list.
2. Run interactive rebase:
`git rebase -i HEAD~3`

3. Reorder commits so that about.txt is committed first.

4. Reword the message Create services.txt → Add services section.

__Split a Commit (Advanced Interactive Rebase)__

1. On main, make a single commit that adds two files at once:
    - team.txt → contains Team member list.
    - roles.txt → contains Team roles and duties.
2. Run interactive rebase:
`git rebase -i HEAD~1`

3. Mark the commit as edit.
    
4. Use:
`git reset HEAD^` (what does this `^` symbol in the command even mean?)
    - Commit team.txt separately with message Add team member list.
    - Commit roles.txt separately with message Add team roles.
    
5. Continue the rebase so history has two neat commits instead of one.

