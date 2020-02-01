# MiniProject1

**Project Description:** This document explains how the usage of Git, Docker, automated testing, and continuous integration can improve the productivity and competitiveness of a company. In addition, this document also provides explanations around the usage of **Vi** and **GitFlow**.

**Group Members**: Kamal Bhagat & Hiren Rana

## Git

As mentioned in the lecture, Git is one of the most widely used version control system around the world. It was originally developed in 2005 by Linus Torvalds, who created Linux operating system kernel. Git is also open source project with very great documentation, including tutorials and dedicated web sites. In addition to that, Git also provides the functionality,performance, security, and flexibility so that it allows teams across the world to work efficiently on their applications. If the organization decides to implement Git in their projects, it would certainly reduce team’s communication overhead and increase release velocity. Each developer in the team is allowed to work independently on their separate branches of feature development and then, eventually merging those changes together.

For example, to submit this assignment, I created branches to work on the first part of the assignment and Hiren Rana created another branches to work on last part of the assignment. By utilizing Git, we both can work on the same assignment as shown below in the figure. Once the changes were committed, each of us are responsible to review each other’s pull requests to make sure that, there is not any conflict. Finally, we can merge all those branches, in order to complete high quality assignment. 

Git allows developers like Hiren Rana and Kamal Bhagat, to release their applications in production environment at faster rate. It certainly creates agile workflow for developers so that they can work on small changes for the application frequently and then, have those changes release in the production with the process of creating feature branches, distributed development, and pull requests.

![Git Example](/images/git.PNG)

[https://www.atlassian.com/git/tutorials/why-git](https://www.atlassian.com/git/tutorials/why-git)

## Docker

Docker is specifically designed so that software engineers can build, ship, and run any business critical applications in production level. User is able to build out and share containers. That way, it will automate the development pipeline from a single environment. There can be multiple containers in the pipeline and each of these containers refers to the app or certain system.

For example, if the user is trying to create web application, then the user needs to make sure that following items are there and working:

 - Database that can store enough data related to application.
 - Accessible Front-end (UI).
 - API layer to enable communication between the front-end and the database.
 - To host the UI and API, need to have web server.

If the organization does not implement Docker, then they would have to manage each of listed items very manually. By having manual process in placed, it becomes hard for developers to keep track of environments, services, and data processes. This is where Docker and containers come in very handy by containerize all of the listed items and simply have the web application running with single command. As mentioned on their website, “Docker is the de facto developer standard for building and sharing apps that enable simplicity, agility and choice for software development across any infrastructure so that you can get your job done and deploy your applications faster.” As a result, it helps developers speed up their workflows and have applications deploying in the production environment at faster rate.

[https://www.docker.com/why-docker](https://www.docker.com/why-docker)

## Continuous Integration

By utilizing tools like Git and Docker, it allows users to have continuous integration and delivery environments for any given applications. Features like Git hooks, can also allow users to perform scripts when specific events take place inside the repository. Continuous integration can certainly allow code from different developers in your team, to be dependable. That way, it can automate the deployment process and it allows developers to deploy code from local branches to various preferred servers.

Manual testing can be time consuming and prone to human error. Not only it slows down the deployment process, but the quality of software can also be questionable. If the organization decides to automate the manual test cases and have those test cases added to deployment pipeline, then it ensures that quality of the software is being tested efficiently.

GitFlow branching model can also be another example for continuous integration. When the feature branch is created and merged to master branch, then the continuous integration verifies that new changes do not create any conflicts with previous version of the application. The quality gates in the continuous integration should be placed in the correct regions to mitigate any conflicts or defects. There is also misconception that, by having these quality gates in the continuous integration pipeline, the application would be bug-free; that is certainly not the case. However, it locates the bug in the pipeline, so that developers can work on resolving it.

[https://codeship.com/continuous-integration-essentials](https://codeship.com/continuous-integration-essentials)

## GitFlow

GitFlow is way to collaborate codes via teams using a method called **branching**. Using branching, each team member is able to work on various aspects of their code in parallel to other aspects. This allows work to be split and each split branch focused on by different individuals. Once branches are completed and ready, the codes can be **merged** back into a master branch prior to release. Once a code is ready for release, it can be cloned and branched off into a develop mode. This code is then run to ensure any bugs are identified and fixed. If there is a need to edit the source code, the respective teams can make the edits merge the branches back into the master branch and a new testable code be branched off to test in development.

[https://datasift.github.io/gitflow/IntroducingGitFlow.html](https://datasift.github.io/gitflow/IntroducingGitFlow.html)

### Repository

A repository is the overall **folder** for a project. All of the respective files are contained within a repository including branches, README, requests, etc. A simple repository can be created through Github main page. This is simply a folder which will contain all of the respective parts of the overall project.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Clone

A clone is used to make a copy of a repository. The purpose of this clone is so edits and changes can be made without it affecting the actual released repository that is stored online. The changes to a clone can be pushed into the online repository once a change is made and completed. A clone can be created through Github.

![Git Clone Example](/images/clone.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Fork

A fork is similar to a clone in which it is a copy of a repository. Similarly to a clone, changes can be made to this forked repository without it affecting the master repository (the original). The difference is a fork is linked to the overall repository wherein a user can ask to have their changes pushed to the original file.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Branch 

A branch is a subset of a master wherein users can work on a separate copy in parallel to other branches and then merge these branches back to the master once complete. Typically a branch is created through **git checkout –b 'newbranch'**. Below is the example: 

![Git Branch Example](/images/branch.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Commit

A **commit** is essentially saving a file. The changes made to the branch or file is saved ready to be merged to a master branch. A commit is performed through **git commit**. Below is the example: 

![Git Commit Example](/images/commit.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Merge 

A merge takes changes from one branch and adds it into a different branch or to the master branch. A merge can be completed through a pull request.

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Checkout 

A checkout is switching between different branches. This can be done through **git checkout [name of branch]**. Below is the example: 

![Git Checkout Example](/images/checkout.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Push

Push allows a user to submit their files to a repository. This can be done through **git push [name of master]**. Below is the example: 

![Git Push Example](/images/push.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Pull 

A pull allows a user to grab files from a master or different file so that it can be edited so that you are working from the current, latest file. Below is the example: 

![Git Pull Example](/images/pull.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Remote Add 

Remote Add is similar to clone in the sense that it adds a remote repository so that it can be worked on and collaborated with various users. This can be done through  **git remote add [shortname] [url]**. Below is the example: 

![Git Remote Add Example](/images/remote_add.png)

[https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes](https://git-scm.com/book/en/v2/Git-Basics-Working-with-Remotes)

### Status

Status allows a user to see the status of a file or commit. This can be done through **git status**. Below is the example: 

![Git Status Example](/images/status.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)

### Master

The Master Branch is the main local path of the repository. In a collaboration sense, branches are created from the master branch. Each branch is worked on and then merged with the master. Below is the example: 

![Git Master Example](/images/master.png)

[https://help.github.com/en/github/getting-started-with-github/github-glossary](https://help.github.com/en/github/getting-started-with-github/github-glossary)