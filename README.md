# learnable-journey
This is the first Github task on learnable-24

## Explain version control
Version control is a system that helps developers to track changes and manage their code by keeping up to date every changes made to the code and can also go back to a marked point at every point in time.

## Explain the difference between git and github
### Git
Git is a version control system which helps developers to manage and track their code changes on their local system.

### Github
Github is an online or a web-based platform which uses git to manage repositories and allow developers to collaborate while working on a repository from different locations without conflicts on the project.

## List 3 other github alternatives
1. GitLab
2. Gitbucket
3. SourceForge

## Explain the difference between git fetch and git pull
### Git fetch
Git fetch is a command which allows developers to update the local codebase with the remote changes made but does not attempt to merge the remote changes.
The command for this is `git fetch`

### Git pull
Git pull is a command which is a combination of git fetch and git merge. It updates the local repository with the remote changes and attempts to merge the changes to your local branch. The git pull command updates both your local reference and your working directory.
The command for this is `git pull`

## Explain in simple terms git rebase and the command for it
Git rebase is a command used to apply your changes on top of another branch. It helps to keep the project history clean. Instead of creating a merge comit, it rewrites the history by placing your changes on top of the target branch.
For example, If you are working on another branch, and you want to update the main branch with the latest feature directly, the git rebase command rewrites it to the main branch directly as if the commit was made on the main branch.
The code for it is `git rebase <branch to update changes to>` e.g `git rebase main`

## Explain in simple terms git cherry-pick and the command for it
Git cherry-pick is a useful command in git used to apply a particular commit from one branch to another.
Take for example, you are working on the main branch, and you want to apply a specific commit from branch B without merging all commits from the branch, all you have to do is to get the hash of the particular branch you want to apply its commit and use the git cherry-pick command and specify the hash of the commit you want to apply.
The command for it is `git cherry-pick <hash of commit>`