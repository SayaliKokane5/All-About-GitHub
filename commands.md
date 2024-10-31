Setup

Initialize a Repository: git init - Initializes a new Git repository.
Clone a Repository: git clone [url] - Copies a repository from a remote location.
Set User Information: git config --global user.name "Your Name" and git config --global user.email "your.email@example.com" - Configures your name and email for commits.

Version Control

Check Status: git status - Shows the status of changes in the working directory.
Add Changes: git add [file] - Stages changes for the next commit.
Commit Changes: git commit -m "Your message" - Saves changes to the local repository.
View History: git log - Displays the commit history.
Undo Changes: git reset HEAD~1 - Unstages changes, git checkout -- [file] - Discards changes in the working directory.

Branching

List Branches: git branch - Lists all branches.
Create a Branch: git branch [branch-name] - Creates a new branch.
Switch Branches: git checkout [branch-name] - Switches to a different branch.
Merge Branches: git merge [branch-name] - Merges a branch into the current branch.

Collaboration

Add Remote Repository: git remote add origin [url] - Adds a remote repository.
Push Changes: git push origin [branch-name] - Pushes changes to the remote repository.
Pull Changes: git pull origin [branch-name] - Fetches and merges changes from the remote repository.
Create a Pull Request: Navigate to GitHub's web interface and use the "Compare & pull request" button.

Advanced Commands

Stash Changes: git stash - Temporarily stores changes to be reapplied later.
Rebase: git rebase [branch] - Reapplies commits on top of another branch.
Tagging: git tag -a [tagname] -m "message" - Creates an annotated tag.
