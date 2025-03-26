Popular Git Hosting Services:

GitHub, GitLab, Bitbucket, Azure DevOps, SourceForge.

Types of Git Repositories:

Bare repositories (used for sharing),

Non-bare repositories (used for development).

Git and File Deletion:

Files can be removed with git rm. Git tracks the deletion and reflects it in the next commit.

Creating Aliases in Git:

Use git config --global alias.<alias-name> '<git-command>'.

Renaming a Branch in Git:

First, rename locally using git branch -m <old-name> <new-name>. Then delete the remote branch and push the renamed one.

Git Fetch vs Git Pull:

git fetch retrieves updates but doesn't apply them. git pull retrieves and applies updates to your working directory.

Git Rebase:

Reapplies commits on top of another base tip. It’s useful for maintaining a cleaner history.

Creating a Git Repository:

Initialize with git init or clone an existing repo with git clone <url>.

git remote vs git clone:

git remote manages remote connections. git clone fetches the repository to create a local copy.

Benefits of Pull Requests:

Collaboration, code review, and tracking changes before merging.

Git Bundle:

A compressed snapshot of a repository, great for offline usage.

Advantages of Git Over SVN:

Distributed version control, lightweight branches, faster operations, and better merging support.

Git Stash:

Temporarily saves changes without committing, allowing you to work on another task.

Revert a Commit:

Use git revert <commit-hash> for public commits. Creates a new commit to undo changes.

Reverting vs Resetting:

Revert undoes specific commits without changing the history. Reset changes the branch pointer and working directory.

git reflog vs log:

git log shows commit history. git reflog tracks actions in your repository.

HEAD in Git:

Points to the current branch or commit in your working directory.

Purpose of git tag -a:

Creates annotated tags for marking significant commits.

HEAD, Working Tree, Index:

HEAD refers to the latest commit; Working Tree is your current files; Index is the staged snapshot for the next commit.

Resolving Conflicts in Git:

Open conflicted files, manually edit and fix conflicts, then stage and commit changes.
