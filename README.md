
# udacity_repo
This is a repository to gain familiarity with Git &amp; Github

# git commands

# Create a new branch and witch to that branch

git checkout -b 'branch_name'

# List all available branchs 
git branch


git pull origin <branch_name> 

origin: Refers to the default name of the remote repository you are pulling from (this is usually set during git clone).

<branch_name>: Specifies the branch you want to pull updates from (e.g., main, develop).

Purpose of git pull origin

To update your local repository with the latest changes from the remote repository.

It combines two Git commands:

git fetch: Downloads the changes (commits, files, etc.) from the remote repository but does not merge them into your local branch.

git merge: Integrates the fetched changes into your current local branch.

By default, git pull performs both fetching and merging in one step, saving time and effort for the user.
