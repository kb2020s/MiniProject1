# MiniProject1

## GitFlow

GitFlow is way to collaborate codes via teams using a method called **branching**. Using branching, each team member is able to work on various aspects of their code in parallel to other aspects. This allows work to be split and each split branch focused on by different individuals. Once branches are completed and ready, the codes can be **merged** back into a master branch prior to release. Once a code is ready for release, it can be cloned and branched off into a develop mode. This code is then run to ensure any bugs are identified and fixed. If there is a need to edit the source code, the respective teams can make the edits merge the branches back into the master branch and a new testable code be branched off to test in development.

[https://datasift.github.io/gitflow/IntroducingGitFlow.html](https://datasift.github.io/gitflow/IntroducingGitFlow.html)

## Repository

A repository is the overall **folder** for a project. All of the respective files are contained within a repository including branches, README, requests, etc. A simple repository can be created through Github main page. This is simply a folder which will contain all of the respective parts of the overall project.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Clone

A clone is used to make a copy of a repository. The purpose of this clone is so edits and changes can be made without it affecting the actual released repository that is stored online. The changes to a clone can be pushed into the online repository once a change is made and completed. A clone can be created through Github.

![Git Clone Example](/images/clone.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Fork

A fork is similar to a clone in which it is a copy of a repository. Similarly to a clone, changes can be made to this forked repository without it affecting the master repository (the original). The difference is a fork is linked to the overall repository wherein a user can ask to have their changes pushed to the original file.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Branch 

A branch is a subset of a master wherein users can work on a separate copy in parallel to other branches and then merge these branches back to the master once complete. Typically a branch is created through **git checkout –b 'newbranch'**. Below is the example: 

![Git Branch Example](/images/branch.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Commit

A **commit** is essentially saving a file. The changes made to the branch or file is saved ready to be merged to a master branch. A commit is performed through **git commit**. Below is the example: 

![Git Commit Example](/images/commit.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Merge 

A merge takes changes from one branch and adds it into a different branch or to the master branch. A merge can be completed through a pull request.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Checkout 

A checkout is switching between different branches. This can be done through **git checkout [name of branch]**. Below is the example: 

![Git Checkout Example](/images/checkout.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Push

Push allows a user to submit their files to a repository. This can be done through **git push [name of master]**. Below is the example: 

![Git Push Example](/images/push.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Pull 

A pull allows a user to grab files from a master or different file so that it can be edited so that you are working from the current, latest file. Below is the example: 

![Git Pull Example](/images/pull.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Remote Add 

Remote Add is similar to clone in the sense that it adds a remote repository so that it can be worked on and collaborated with various users. This can be done through  **git remote add [shortname] [url]**. Below is the example: 

![Git Remote Add Example](/images/remote_add.png)

[https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)

## Status

Status allows a user to see the status of a file or commit. This can be done through **git status**. Below is the example: 

![Git Status Example](/images/status.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

## Master

The Master Branch is the main local path of the repository. In a collaboration sense, branches are created from the master branch. Each branch is worked on and then merged with the master. Below is the example: 

![Git Master Example](/images/master.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)