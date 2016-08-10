<!--
Creator: <Name>
Market: SF
-->

![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# Git and GitHub

### Why is this important?
<!-- framing the "why" in big-picture/real world examples -->
*This workshop is important because:*

Git is the industry standard tool for version control. That is, when you write code, git helps you track all of the changes that you've made over time to ensure that no work is lost. GitHub is the tool that takes git and makes it collaborative. It helps you make sure that every developer's version of the code is the same between different computers. GitHub has also allowed unprecedented sharing of code and tools through the open source movement. You can freely access any code that somebody has made public and use it in your own projects.

### What are the objectives?
<!-- specific/measurable goal for students to achieve -->
*After this workshop, developers will be able to:*

- explain the uses of Git and GitHub for tracking their changes and collaborating on projects.
- draw a model of local, remote, and working copies of their repositories.
- write some code to improve their work, commit the changes, and write a strong commit message.
- deploy their first live website using gh-pages.
<!-- - navigate to old commits in their projects both on their machine and on GitHub. -->

### Where should we be now?
<!-- call out the skills that are prerequisites -->
*Before this workshop, developers should already be able to:*

- navigate the files in their computer using terminal
- create and save a basic HTML or CSS file.
- access GitHub with their own user account.

## Git and GitHub

You'll be using git and GitHub every day throughout this course (and as a developer in the industry) for version control. **Version control** is a system that records changes to a file or set of files over time so that you can recall specific versions later.

More specifically, **a version control system allows you to:**

* Review changes made over time
* Revert files (or an entire project) back to a previous state
* Collaborate on a project with other developers
* Track down the origin of bugs in the code
* Back up your projects on a remote server

**Git** is a version control system and **GitHub** is a social network built around git.

Git stores information about your project in a **repository** (often called a repo). A git repository holds the current version of your project's files, as well as the complete history of all past versions.

Your computer holds a **local repository**. It's a copy of all of the changes you've ever committed on your machine. GitHub holds a **remote repository**. It's a copy of all of the changes you've ever committed and pushed to the web.

When you're working, you are editing a working copy. You save it with `cmd` + `s` just as you've always saved documents on your computer. You should be saving **constantly**.

When you're ready to save a "state of the code"

### Visaulizing your workflow
<figure>
  <img src="https://www.git-tower.com/learn/content/01-git/01-ebook/en/01-command-line/04-remote-repositories/01-introduction/basic-remote-workflow.png" alt="Local and remote">
  <br>
  <figcaption>The table below has all of the key words from this diagram bolded. </figcaption>
</figure>

### Git Basics

| Action | Command |
| :--- | :--- |
| Create new git repository | `git init` |
| Copy (**clone**) an existing repository from the internet (remote) onto your computer (local)| `git clone <repo url>`|
| Check status of git repo | `git status` |
| Check differences since last commit | `git diff <filename>` |
| Add file to git repo (**stage** for commit) | `git add <filename>` |
| Add (**stage**) all edited files in the current directory | `git add .` |
| **Commit** (save) a version into the local repository | `git commit -m "message describing changes"` |
| **Push** commits to GitHub (remote repository) | `git push <remote> <branch>` |
| **Pull** commits from the remote repository | `git pull <remote> <branch>` |
| Show version history | `git log <filename>` |
| Get help with git commands | `git help <command>` |






### Check for Understanding

<details>
  <summary>In pairs at the board, draw a diagram that shows the commands you might use over time and the impact they would have on your local and remote repositories. Label the repositories, your machine, GitHub, and</summary>
  <p></p>
</details>

## Independent Practice
Refine the skills covered in this workshop with this [training](#)

## Closing Thoughts
- review objectives & hierarchy of importance
- look ahead & link to future workshops
- clarify expectations and what developers should know by now
- reiterate “the why” with a perspective of your intentions
- create an active recall
- Check for understanding

## Additional Resources
- [External Resource](#)
