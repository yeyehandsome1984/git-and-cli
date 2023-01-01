# Lesson

## Lesson Overview

Code Version Control such as GIT is a mandatory tool for developers to collaborate in building and releasing software. Without code version control, the effort to integrate codes written by multiple developers become impossible. GIT has been a popular choice and in this program, we will be using GitHub.com for all lesson content and homework submission. This will help learners to become familiarized with GIT. The mastery of GIT and the use of GitHub takes time. Learners only need to know enough to obtain lesson materials and submit homework by the end of this lesson.

---

## Part 1 - What is GIT?

### Video Introduction

[![GIT Intro by Mosh](https://i.ytimg.com/vi/2ReR1YJrNOM/maxresdefault.jpg)](https://youtu.be/2ReR1YJrNOM)

### Common Misconceptions

1. GIT is the Code Version Control tool. GitHub.com is a web platform that utilizes GIT. BitBucket is a GitHub competitor.
1. Repository basically means a storage space. In GIT, it is a place where we store codes and files related to software.
1. Since GIT is distributed, there is no single source of truth. But there will always be a local repository and multiple remote repositories.

**How is GIT Distributed?**

<img src="./assets/images/distributed-diagram.png" />

- When we FORK a repository shown at (1), we are copying a repository from one source (other account) into our own account.
- In most cases, we would clone from the repository resides in our own account as shown at (2). Clone means to make a copy from our remote repository (in GitHub) to our local machine.
- The repository in our local machine and our remote repository will be linked. By default, the link alias is named `origin`.
- We can also create additional link shown as (3). We can add a new remote link alias to the upstream remote repository we forked from. 

> A "link" is a layman term to help learners better understand. The technical term is [tracked remote repository](https://git-scm.com/docs/git-remote).


### Steps for Homework

Every lesson would require learners to:

1. `Fork` repository from Trent's to personal 
1. `Clone` from personal remote repository to local machine
1. Make changes to the repository (such as doing homework)
1. Stage the changes by using `add` command
1. Commit the staged changes by using `commit` command
1. Finally, push the commit to personal remote repository using the `push` command

With this, instructors will be able to receive learners' homework on their GitHub repositories.

---

## Part 2 - Forking & Cloning Repositories

Step 1: Visit the lesson URL: https://github.com/trent-f2f-bootcamp-pt/git-and-cli

Step 2: Fork the repository

<img src="./assets/images/fork-step-2.png" />

Step 3: Verify that the repository is forked

<img src="./assets/images/fork-step-3.png" />


---

## Part 3 - Commit Changes and Push Commits

{{Input concepts, replicable steps & Code Samples}}

END