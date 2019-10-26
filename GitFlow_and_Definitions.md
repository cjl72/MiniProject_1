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
  1.  A commit is a revision or an edit on your project. This can be done by clicking the edit button on the top right of your repository and proceeding to edit your document and hit commit changes on the bottom left when finished. This will document the time of changes and what changes.
  2. The command for this is git commit -m "Commit Message"
* Merge
  1. When looking at all the branches you can put all the seperate branches into on single branch. This can be useful when there are so many branches created it is hard to keep track of. The basic understanding is taking all these different committs and logging them all together.  This is a merge.
  2. The command is git merge <branch_name>
* Checkout
  1. he git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.
  2. The command is git checkout <branch_name> and git checkout -b <branch_name> checks out and creates a new branch.
* Push
  1. Pushing sends your local commits to the remote repository.  
  2. the command is git push <repository url><branch>
* Pull
  1. Pull will get the latest version of the repository.  Gets the changes from remote repository and makes it local
  2. The command for this is git pull <branch_name><repository url>
* Remote Add/Remove/Show
  1. To add a remote repository you can use the command git remote <command><remote_name><remote_URL>
  2. git remote remove origin is how you remove the remote repository connection, with older versions it is git remote rm origin
  3. you can use git remote -v to show the urls stored with the remote names
* Status
  1. git status returns the current state of the repository.  Can show if file is waiting on commits or if it is clean.
* Master Branch
  1. As it can be seen by the above picture, the master branch is the home base per say.  The master branch ponter moves forward as commits are made.  It can be seen as a final product after all the commits are pushed to it.

Here is a quick tutorial on Git: [Git Tutorial](https://www.youtube.com/watch?v=USjZcfj8yxE)
