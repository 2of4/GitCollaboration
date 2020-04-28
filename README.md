# GitCollaboration
# 2020-04-24 Git Collaboration Notes
Git Collaboration Workshop
- 'git clone <URL>': downloads the repository from the web to our computer
	- Make sure you don't nest this command in another repository
	- just like 'git init' do this only once per repository
## Branches
- 'git branch ,branch_name>': create a new branch
- 'git swtich <branch name>': move to a branch
	- 'git checkout <branch name>': old way of moving to branch
- 'git swtich -c <branch name>': create and move in 1 command
	- 'git checkout -b <branch name>' 

- 'git stash': temp saves current state as commit so you can 'checkout' or 'switch'
	- 'git stash apply' to apply the last stash from the stack


- 'git push origin <branch name>' : pushes branch to the remote
	- this is where you will create the Push Request (online)
	- you merege the PR (and also the branch) by accepting and merging the PR
- don't foret to clean up your branches
- 'git fetch' --prine': clean sup the references in your 'git log --oneline --graph --decorate --all'
- 'git branch -d <branch_name> : delete branch on your local machine
	- it will tell you to move to another branch (e.g., 'master') first

