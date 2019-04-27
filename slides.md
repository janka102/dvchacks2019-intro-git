# Introduction to Git

.max-width-100[![Git Logo](images/git-logo.png)]

???
Welcome to the "Introduction to Git" workshop

---

# Some background

Hi, I'm Jesse.

I was a student at DVC and graduated in 2017. Now I'm at SFSU

I was president of dvcoders for a couple semesters  
One thing I saw was many students who didn't know how to use Git

So here we are!

???
First let me introduce myself...

---

# git init

What is Git?

Git is a version control system (VCS)

That means it keeps track of:

- all changes to a project
- who made the changes
- when they were made
- why they were made

Git can help with projects from one developer to a whole company of developers

Git is powerful!

???
Ok, let's talk about Git...

---

# Getting Git
### [https://git-scm.com/download](https://git-scm.com/download)

**Windows**

[Click here for easiest way to install Git on Windows](https://git-scm.com/download/win)

**macOS**

If you know you have homebrew, then it should be already installed  
Otherwise, [click here to download](https://git-scm.com/download/mac)

**Linux**

[Check here on how to do that for your distribution](https://git-scm.com/download/linux)

---


Once Git is  installed, test it by opening a terminal (or GitBash on Windows) and type

```sh
git --version
```

There shouldn't by any issues.

<hr>

# GitHub.com

Next up is getting an account on [GitHub](https://github.com).

GitHub is a popular hosting site for Git repositories.

---

# Who actually uses Git?

Sure it sounds cool, but is it really going to be useful?

--

*YES!*

Many companies of all sizes use Git on a daily bases to help with managing projects

- [Google](https://github.com/google): [Material Design icons](https://github.com/google/material-design-icons)
- [Microsoft](https://github.com/Microsoft): [VS Code](https://github.com/Microsoft/vscode)
- [Linux](https://github.com/torvalds/linux)
- [DVCHacks](https://github.com/dvchacks)

Git is all around you, you can't get away!

---

# Git terminology

- *repository*: a project folder that has Git enabled
- *clone*: download a repository
- *branch*: separate version of code used to work on features
- *commit*: a short message describing a change
- *remote*: website to store the changes
- *push*: send changes to a remote
- *pull*: get changes from a remote

???
Let's get more familiar with Git

---

# The Git workflow

Start out by cloning a repo: `git clone https://github.com/me/my-project.git`. Then `cd my-project`

1. Create a new branch: `git checkout -b branch_name`
  - *The original branch is no longer affected by any changes here*
2. Make and add changes: `git add myFiles.js`
3. Commit the changes: `git commit -m "I added some code"`
  - Repeat 2 and 3 as needed
4. Switch back to main branch: `git checkout master`
5. **Pull in case someone else made changes**: `git pull`
6. Merge your changes into master: `git merge develop`
7. Repeat 1-7
