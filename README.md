# Reflection
### 1. Steps taken to create/manage branches

  * To create my branches, I used the git command `git checkout -b [branch name]`.  For example, for the header section I created the branch using `git checkout -b feature/header`
  * I then use `git add -A` to stage my changes and use `git commit -m [message]` to commit my changes to the branch before swapping branches using the checkout command
  * When the features are complete and working, I swapped to the main branch and use the git command `git merge [branch name to be merged]`

### 2.how do I handle conflicts
  * For this assignment where we had 2 footers created in both the header and footer features, I ended up having to manually resolve by copying information in the conflict resolver on VS Code into the appropriate section, as the merge feature was trying to create 2 footers
  * In appropriate cases, I can use the option provided by the editor to apply both changes.  We see this in the earlier lab where we applied a header and footer from separate branches into one file.  

### 3. How does the pull request help with ensuring code quality and collaboration
  *  The pull request process allows for multiple people review, comment on, accept, and deny changes before they are committed.  Pull requests allow us to ensure a block of code follows both formatting and quality standards set for the project.
  *  To help further collaboration, pull requests also contain a comment section allowing collaborators to both:
      -  discuss why or why not code should be pushed to main
      -  discuss options or ideas around a block or line of code to improve efficiency and formatting
  *  Overall, pull requests help maintain consistent standards, ensure everyone's contributions are preserved, and support effective team collaboration.
