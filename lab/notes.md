# GitHub lab

## Introduction
At its heart, GitHub is a collaboration platform.
GitHub is also a powerful version control tool.
Issue titles are like email subject lines. They tell your collaborators what the issue is about at a glance. 

Branches are an important part of the GitHub flow because they allow us to separate our work from the master branch. In other words, everyone's work is safe while you contribute.

* Don’t end your commit message with a period.
* Use active voice. For example, "add" instead of "added" and "merge" instead of "merged"


## Markdown
Markdown is one of the most important ways developers can make their communication clear and organized in issues and pull requests.

If you include a task list in the first comment of an issue or pull request, you'll see a progress indicator in your issue list.

Tone doesn't come across as clearly when reading text as it comes speaking face to face, and emojis can be helpful in conveying context and emotions.

## GitHub pages
The _config.yml file is used by Jekyll to store certain preferences about your site (like your theme) and reusable content like your site title and github handle.

## Moving
Text files, like most code files, are easily tracked with Git 📖 and are very lightweight.
binary files like spreadsheets, presentations with slides, and videos don't work well with Git

As we convert your project to a Git repository, it should only include the source code necessary to build or compile your project.

Public repositories on GitHub have a Community score. This score is based on the documentation, and how easy it would be for new users to help out and contribute to your project. 

Protected branches ensure that collaborators on your repository cannot make irrevocable changes to branches. 

It's important to note that public does not equal open source! The license associated with code determines whether or not it is open source. 

Releases are GitHub's way of packaging and providing software to your users. You can think of it as a replacement to using downloads to provide software.

## Merge Conficts
Version control is all about making incremental changes to your code or file base. Merge conflicts happen when someone else made a change on the master branch in the same file and location where you were making changes. This usually happens when someone else merges in their branch before you merge yours.

Notice a new commit has been added. This commit is called a merge commit and marks the point in time when your branch was merged in to master.

Resolving a conflict doesn't automatically merge the Pull Request in GitHub. Instead, it stores the resolution of the conflict in a merge commit and allows you (and your team) to keep working. To resolve a conflict, GitHub performs what is known as a reverse merge. This means that the changes from the master branch were successfully merged into your update-config branch.

Notice there are two distinct sets of conflict markers. This is because multiple sections of the file were modified on both branches, so Git identified the two changes within the file as two separate conflicts