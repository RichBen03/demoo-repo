# Mastered git and github
## Here are some of the commands i learnt and can use very well

**git config --global user.name "Your Name"**
* Sets the name to associate with your commits.
* The --global flag applies the configuration globally (all repositories on your system).

  
**git config --global user.email "you@example.com"**
* Sets your email for commits globally.

**git config --global core.editor "code --wait"**
* Sets the default text editor. Here, "code --wait" sets Visual Studio Code as the default editor.

  
**git config --list**
* Displays all the Git configurations for the system.

**git init**
* Initializes a new Git repository in the current directory.
* Creates a .git directory where all version control files are stored.
* Run this in a project folder to start tracking it with Git.

**git clone <repository-url>**
* Creates a local copy of a remote repository.
* Use this to download a project from a remote repository like GitHub.

**git status**

* Shows the state of the working directory and staging area.
* Tells you if files are staged for commit, modified, or untracked.

**git add <file> or git add .**
* Adds a file (or all changes with .) to the staging area.
* Run git add before committing to include the changes in the next commit.
  
**git commit -m "commit message"**
* Records changes to the repository with a descriptive message.
* Use a clear, concise message explaining the changes.

**git branch <branch-name>**
* Creates a new branch but doesn’t switch to it.
* Useful for developing features without affecting the main branch.

**git checkout <branch-name>**
* Switches to the specified branch.
* Essential for working on different branches or reverting to previous versions.

**git merge <branch-name>**
* Combines the specified branch with the current branch.
* Run this in the target branch (e.g., main) to merge another branch’s changes.

**git log**
* Shows a list of commits in the current branch.
* Provides commit hashes, author, date, and message.
  
**git log --oneline --graph --decorate**
* Displays the log with a compact, graphical history.
* Useful for visualizing branch and merge structure.



