Hello Git and Github

Git Workflow:

    1-Fetch and merge changes from the remote
    2-Create a branch to work on a new project feature
    3-Develop the feature on your branch and commit your work
    4-Fetch and merge from the remote again (in case new commits were made while you were working)
    5-Push your branch up to the remote for review

Git Commands:

    git init creates a new Git repository
    git status inspects the contents of the working directory and staging area
    git add adds files from the working directory to the staging area
    git add filename_1 filename_2 adds multiple
    git diff shows the difference between the working directory and the staging area
    git commit permanently stores file changes from the staging area in the repository
    git log shows a list of all previous commits

Git Backtrack:

    git checkout HEAD filename: Discards changes in the working directory.
    git reset HEAD filename: Unstages file changes in the staging area.
    git reset commit_SHA: Resets to a previous commit in your commit history.

Git Branching:

    git branch: Lists all a Git project’s branches.
    git branch branch_name: Creates a new branch.
    git checkout branch_name: Used to switch from one branch to another.
    git merge branch_name: Used to join file changes from one branch to another.
    git branch -d branch_name: Deletes the branch specified.

Git Teamwork:

    git clone: Creates a local copy of a remote.
    git remote -v: Lists a Git project’s remotes.
    git fetch: Fetches work from the remote into the local copy.
    git merge origin/master: Merges origin/master into your local branch.
    git push origin <branch_name>: Pushes a local branch to the origin remote.

Connecting and pushing to github:
git remote add origin https://github.com/Cynddelw/Git_Cheatsheet.git
git push -u origin master
