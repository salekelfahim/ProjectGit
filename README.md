# ProjectGit
Documentation Git

git add:Moves changes from the working directory to the staging area. This gives you the opportunity to prepare a snapshot before committing it to the official history.
git branch:This command is your general-purpose branch administration tool. It lets you create isolated development environments within a single repository.
git clone:Creates a copy of an existing Git repository. Cloning is the most common way for developers to obtain a working copy of a central repository.
git commit:Takes the staged snapshot and commits it to the project history. Combined with git add, this defines the basic workflow for all Git users.
git config:A convenient way to set configuration options for your Git installation. You’ll typically only need to use this immediately after installing Git on a new development machine.
git fetch:Fetching downloads a branch from another repository, along with all of its associated commits and files. But, it doesn't try to integrate anything into your local repository. This gives you a chance to inspect changes before merging them with your project.
git init:Initializes a new Git repository. If you want to place a project under revision control, this is the first command you need to learn.
git log:Lets you explore the previous revisions of a project. It provides several formatting options for displaying committed snapshots.
git merge:A powerful way to integrate changes from divergent branches. After forking the project history with git branch, git merge lets you put it back together again.
git pull:Pulling is the automated version of git fetch. It downloads a branch from a remote repository, then immediately merges it into the current branch. This is the Git equivalent of svn update.
git push:Pushing is the opposite of fetching (with a few caveats). It lets you move a local branch to another repository, which serves as a convenient way to publish contributions. This is like svn commit, but it sends a series of commits instead of a single changeset.
git remote:A convenient tool for administering remote connections. Instead of passing the full URL to the fetch, pull, and push commands, it lets you use a more meaningful shortcut.
git reset:Undoes changes to files in the working directory. Resetting lets you clean up or completely remove changes that have not been pushed to a public repository.
git status:Displays the state of the working directory and the staged snapshot. You’ll want to run this in conjunction with git add and git commit to see exactly what’s being included in the next snapshot.

