# TXRX GitHub Workshop
## Overview
In this workshop, you will introduce students to GitHub, the most popular git SaaS (software as a service) product for collaboration.

### Instructor Priorities
* Students should understand basic Git commands
	* `branch`/`merge`
	* `add`/`commit`
	* `push`/`pull`
* Student should understand GitHub workflow
	* Create an issue
	* Create a Pull Request
	* Merge a PR into **master** branch

### Instructor Notes
* Lab computers will need to be setup with Git and [GitHub Desktop](https://desktop.github.com/) . Students who choose to use their own laptops will need to have these tools installed as well (we will not be able to troubleshoot issues they may experience on their personal machines)
* Students will need to setup a GitHub account if they don’t already have one
* A demo repository will need to be created for the workshop. We will use this repo to demonstrate the GitHub workflow.
### Workshop Objective
* Students should have a basic understanding of what Git is and how to use GitHub to do work
* Should gain insight on how GitHub can be used for collaborating on **any** kind of project - design, art, blogging, etc.
---
#### Git
From [wikipedia](https://en.wikipedia.org/wiki/Git)
> Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people.

A version control system (VCS) is software system for tacking and managing changes on files.

Git is special because it's a distributed VCS. This is different from a centralized VCS in that a copy of a repository can be on multiple machines. This is Git's killer feature. Its decentralized nature allows it to be better suited to faster workflows, cheaper branching and merging, and more robustness.

Gits basic commands are:
1. `init` - creates a new `.git` directory in current directory (this is what makes a folder a *repository*)
1. `branch` - creates a new timeline
1. `merge` - merges one branch into another
1. `add` - selects lines/files that have been changed onto a staging area
1. `commit` - creates a new point in time based off of changed lines/files in the staging area
1. `push` - uploads local commits to a remote repository
1. `pull` - downloads remote commits to your local repository; this can fast-forward your branch to the state the server is in

#### GitHub Workflow
It is well known that GitHub enables building software collaboratively, but it can be used for so much more.


We will demonstrate this by writing a short story together.

1. Create the repository on GitHub
* We will either need someone to step up and create it for the class or the instructor can do so.

Creating a repo on GitHub is quick and easy.
1. Navigate to [GitHub](https://github.com) (you will need to sign in if not already)
1. Click the green **New Repository** button located on the right side of the screen
1. Name the repo _Collaborative Story_
1. Ensure that the repo is marked as **Public**
1. Ensure that the option to **Initialize this Repository with a README** is checked
1. Select _MIT_ in the **Add a license** drop-down
1. Click the green **Create Repository** button

At this point, we now have a repository that all students can clone to their computers.
