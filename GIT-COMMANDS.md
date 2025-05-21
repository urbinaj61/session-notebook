### Git Commands

- git status (Informs of the status of folders and files within your folder)
- git add . (Adds unassigned files and folders to the staging area)
- git commit -m "" (commits all files and folders in the staging area)
- git push origin main (pushes all commits to our github repo)
- git remote -v (Informs us if we are connected to our remote repo)
- git switch -c branch-name (create new branch and switch to it)
- git pull origin main or git pull origin branch name (pull from github into our local main or branch name repo)

## To create the local repo on github

- Create a new repo on github. This will give you a http and an ssh path.
- Copy the ssh path
- On your local machine type git remote add origin ssh path
