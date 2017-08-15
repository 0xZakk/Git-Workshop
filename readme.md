# Introduction to Git

This 2 hour workshop will walk you through the basics of Git and GitHub.

## Objectives
- Install Git
- Create a GitHub account
- Understand what git is and why developers use it
- Understand repositories, the stage, committing, pushing and pulling
- Understand remote and local
- Understand Forking and Pull Requests

## Installation
_By the end of this section, students should have Git installed on their computers._

For installation instructions, please see [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Windows users will also need to install [Git Bash](https://git-for-windows.github.io)

## Creating GitHub account
_By the end of this section, students should have a GitHub account that they can work with._

Create an account on GitHub by going to [https://github.com](https://github.com) and Signing Up for an account. 

## Introduction to Git
_By the end of this section, students should be familiar with what Git is and why it's important to learn._

Before we dive in to learning Git, it makes sense to spend some time
understanding the reasoning for learning Git.

Git is a version control tool. It keeps track of changes (by line)
across a collection of files. When we use Git, we can see what changes
we made and seamlessly merge them with changes our coworker made.

If you've worked with track changes in Microsoft Word, then you're
familiar with part of what Git does. Track changes will track any
changes (inserted text, deleted text, etc) to a document. It will mark
those changes by highlighting them in red or green. Git does this. It
also does a lot more. For example, if you and your coworker are writing
a memo using Word and managing your changes using track changes - how do
you keep track of which version is the final version? A common solution
to this problem is to make a copy of the memo and add your initials to
the file name as well as the date and time so that you can keep track of
different versions of the memo. Someone then has to manually add any
changes you make to their version, or vice versa. What a pain!

Imagine if we had to do something like that with a codebase? The
codebase for even a simple application can be many files. It would take
forever and be extremely error prone! So, developers use Git - a tool to
take care of that task.

You designate a folder for Git to watch (called a repository) and Git
will track all changes to any document inside that folder. You then save
your changes and push them to a central version of the set of files. Git
tracks changes line by line and can handle merging changes between
different versions of documents for you.

## Working With Git
_By the end of this section, students should understand what a repository is and how to create one. They should also understand how Git tracks changes to files, how to stage and commit changes and then push them to GitHub._

Create a repository: `git init`
Saving Changes:
  1. `git add -A`
  2. `git commit -m "a commit message"`
Pushing changes: `git push origin master`

## Working with Remotes
_By the end of this section, students should understand how to work with remote repositories hosted on GitHub._

The remote version of the repository is the centralized version of the
file system that everyone will work from. Any changes we make will need
to be synced with the remote repository before our coworkers can see
them.

## Working with Others
_By the end of this section, students should understand how to Fork a repository and make a Pull Request_

We don't always want to give everyone direct access to the central
version of our codebase - think of a contractor going rogue! So instead,
we allow them to Fork the repository and make Pull Requests.

Forking a repository takes the remote/central version and makes a copy
of it that we control. We can then clone that repository and work on the
codebase - the forked version of the repository if ours. We can commit
changes and push them to our fork. When we want to submit our changes
(and get paid that $$$ for our work), we do so with a Pull Request on
the original repository.

## Next Steps
That's it for today! Here are some resources to further your understanding of Git:
- [Git Desktop App](https://desktop.github.com)
- [Pro Git](https://git-scm.com/book/en/v2)
- [Try Git](https://try.github.io/levels/1/challenges/1)
- [Atlassin Git Tutorials](https://www.atlassian.com/git/tutorials)
