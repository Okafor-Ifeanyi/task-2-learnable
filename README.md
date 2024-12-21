# Task 2: Learnable - Version Control Check

## Summary
This task is designed to test the ability to use a version control, specifically Git, to track changes in a project. The task requires the student to 
- create a new repository
- clone into it on, 
- create and checkout to develop, 
- make change to the readme by answering the questions below, 
- add files, commit changes
- Push the branch to GitHub and create a pull request to the main branch..


## Questions
1. Explain version control.
2. Explain difference between git and github
3. List 3 other github alternatives
4. Explain the difference between git fetch and git pull,
5. Explain in simple terms git rebase and the command for it
6. Explain in simple terms git cherry-pick and the command for it 

### Explain Version Control
Version control is a system that records changes to one or more files or collections of files over time so that one can recall specific versions of a project by author, date, or by differences. It is a way to track changes in a project and collaborate with others on the project.

### Explain difference between git and github
| Git | Github |
|----------|----------|
| Git is a popular version controller that tracks code changes, who made the change and collaboration     | Github is a code hosting application for version control and collaboration, it lets you and others work together on projects from anywhere. |

### List 3 other github alternatives
1. Gitlab
2. Bitbucket
3. Azure DevOps

### Explain the difference between git fetch and git pull
__git fetch:__ This command is used to download the latest data from a remote repository and update the local repository. It does not merge the data into the local repository. It is used to update the local repository with the latest data from the remote repository.

__git pull:__ This command is used to download the latest data from a remote repository and merge it into the local repository. It is used to update the local repository with the latest data from the remote repository and merge it into the local repository.

### Explain in simple terms git rebase and the command for it
__git rebase:__ This command is used to reapply the commits of your branch on top of another branch. It is used to update the local repository with the latest data from the remote repository and merge it into the local repository. 

*cmd* - `git rebase <branch-name>`
or
*cmd* - `git rebase <basebranch> <topicbranch>`
or
*cmd* - `git rebase --onto <basebranch> <divergebranch> <topicbranch>`

### Explain in simple terms git cherry-pick and the command for it
__git cherry-pick:__ This command is used to apply the changes introduced by some existing commit. It is used to apply the changes introduced by some existing commit to the current branch. 

cmd - `git cherry-pick <commit-hash>`


>> _Author: *Okafor Ifeanyi*_