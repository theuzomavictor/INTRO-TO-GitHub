# Introduction to GitHub

![](https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png)

## Table of content
1. Introduction.
2. What is GitHub?
3. Why Git?
4. Git vs. GitHub.
5. Clone (How to clone from GitHub).
6. Pull request (How to do a pull request).
7. Commits (How to do a commit).
8. GitHub Desktop vs. GitHub CLI.
9. Conclusion.

## Introduction
GitHub is a web-based hosting service used to host Git repositories. In computing, a repository or "repo," as defined by the Oxford dictionary, is a central location where data is stored. GitHub is a very important tool for developers, software engineers, and technical writers. It is extremely important to learn how Git and GitHub work. Usually, Git stores files locally on your computer, but GitHub allows you to have an online location where your files and version history are stored.

## What is GitHub?

GitHub is an online software development platform used for storing, tracking, and collaborating on software projects. It allows you and others to work on projects from anywhere in the world. It is used to interact with version control software like Git.

## Why Git?

Git is a distributed version control system. It is distributed in the sense that every contributor working on a team project has a copy (repo) locally on his or her computer. It's software that records versions or changes to your files. It allows you to recall specific versions of your files at any given time. Okay, here's an illustration: 
Let's say I own a company that develops websites and a young man contacted me to ask for assistance in designing a website. We began the project only after both parties had agreed. Once we were done, we forwarded him a link to his website. He took a look at it and made a change request to us. He chose to stick with the original design after three rounds of reviews and revisions, which means we will have to restart the entire coding procedure. Without Git, that would have been a very frustrating experience. We'll just have to go back and give him the first/original version of the project. Now you know why Git is significant.
So basically, Git allows you to work on new features without having to mess up the initial code.

## Git vs GitHub

You now know what Git and GitHub are used for. Let's examine some of their main distinctions.

* **Introduction:**
GIT was first introduced in April 2005.
GitHub was first introduced in October 2007 and later developed in April 2008.
* **Ownership:** 
Git is maintained by Linux. 
GitHub is maintained by Microsoft.
* **Application:** 
Git is a command line tool. 
GitHub has a graphical user interface(GUI).
* **Storage:** 
Git is installed locally on the system for use and does not require the internet. GitHub can be accessed on the web. It needs an internet connection.
For more information, see [Git vs GitHub.](https://www.interviewbit.com/blog/git-vs-github/?amp=1)

## Clone
On GitHub, cloning entails downloading and copying the codes and files that are present in the repository. Before we begin, you should know some of the basic commands of Git.
Now, to clone a repo in GitHub, use the following order:
1. Head over to your GitHub profile.
2. Click the new icon.
![](20221006_233318.png)
3. Name your repo.
![](20221006_233504.png)
4. Add a Readme.md file and create.
![](20221006_233642.png)
5. Click the code icon, and copy the URL.
![](20221006_233824.png)
6. Now, head over to your terminal. use the command ``` git clone [paste the URL here] ```.
7. Finally, navigate into the repo using the command ``` cd [folder name] ```. In our case, it is ``` cd github```. 

You have successfully cloned the repository.

## Commits
Commits are safe points. Adding commits records your progress and changes as you work.
To do a commit, use the following order:
1. Stage the files you want to commit. Staging files gives Git permission to track your files. To stage a single file, use the command ``` git add [file name] ```. To stage multiple files, use the command ```git add . ``` or ``` git add --all ```.
2. Commit the file/files. To commit, use the command ``` git commit -m "This is for messages" ```. The ``` -m "Adds a descriptive message" ```. 

Your file or files have been successfully committed.

## Pull request
Pull request is a way to contribute/collaborate to a project.  
To do a pull request in GitHub, use the following order:
1. Fork the repo you want to make changes to. A fork is a copy of a repo.
![](20221007_224409.png)
2. Create fork.
![](20221007_224618.png)
3. Click the code icon, copy the URL, and head over to your terminal to clone it.
![](20221007_224943.png)
4. In your terminal, use the command ``` git clone [paste URL here] ```. Click Enter.
Your output is similar to this:
![](pull%204.png)
5. Navigate into the repository directory. Use the command ``` cd [Directory name] ```
6. Go to the project you wish to make changes to.
7. Save your changes, add them to the staging area, and commit. To add to the staging area, use the command ``` git add . ```. To commit, use the commmand ``` git command -m "" ```Leave a descriptive message about the changes between the quotation marks. Click Enter.
8. Push your changes back to the main branch. Use the command ``` git push origin main ```. Click Enter.
Your output is similar to this:
![](pull%205.png)
9. Return to your GitHub account to verify the changes in the forked repo.
10. Click pull requests > New pull request.
![](20221007_225142.png)
11. Click create pull request.
![](20221007_225244.png)
12. Finally, leave a comment and create pull request.
![](20221007_235027.png)


And your pull request was successfully created.

## GitHub Desktop vs. GitHub CLI

For new users who find it challenging to use the command line interface, **GitHub Desktop** is a fantastic tool. It provides lovely and precise buttons for each Git command, so that the need for the command line is never felt.

The **GitHub CLI** is a terminal interface. Using the GitHub CLI, you can interact with your code and perform actions related to pull requests, issues, and other GitHub tasks directly in your terminal. 

## Conclusion
Learning to use Git and GitHub can be overwhelming, but it is a very rewarding skill. This article's goal is to make GitHub and the Git concept more clear to you. Now, it is time to explore these things yourself. All the best!