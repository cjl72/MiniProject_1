# GitFlow and Definitions
[Back To Home](https://github.com/cjl72/MiniProject_1)
## GitFlow
GitFlow is a branching model for Git, created by Vincent Driessen. It has attracted a lot of attention because it is very well suited to collaboration and scaling the development team.  As it can be seen in the image below, there are multiple different levels to gitFlow and how it operated with the master branch and develop branch being the main branches in the gitFlow workflow.  Following this type of workflow is beneficial on all levels for collaboration and keeping track of the contributors.

Here is a quick easy tutorial on gitFlow: [gitFlow Tutorial](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow)
![GitFlow Demo](https://github.com/cjl72/MiniProject_1/blob/master/git-model.png)

### Git Features
* Repository
  1. The main basic function of GitHub is repositories. A repository if where the files for a single project get stored, and they are easily accessed through a specific URL.
  2. The command for this is git init, this will turn a directory into an empty repository.
* Clone
  1. As for cloning, this function as stated before is downloading a copy of the source code, or text. The copy on your computer will sync with the original file on GitHub, practically acting as a backup for your project.
  2. The command for this is git clone <remote_URL>
* Fork
  1. A fork is a copy of a repository, this allows someone to make changes that will not go directly to the repository.
  2. Forking uses the same command as cloning.  On github there is a fork button seperate from the clone button, but in bash they are they do the same thing.
* Branch
  1. The connections between all the pushing and pulling is documented as branches. These branches can all be seen in the branches tab on the main page of your repository. It will show the branches that you have pushed to, branches that people have committed to, and even branches that noone has committed to recently.
  2. git branch <branch_name> will create a branch and branches can be viewed with git branch -a and deleted with git branch -d<branch_name>
* Commit
* Merge
* Checkout
* Push
* Pull
* Remote Add/Remove/Show
* Status
* Master Branch

Here is a quick tutorial on Git: [Git Tutorial](https://www.youtube.com/watch?v=USjZcfj8yxE)
