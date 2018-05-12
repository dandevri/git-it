# GitHub Education

Git let's you track progress over time. Save snapchots to retrace steps. Up-to date with latet work. Work in parallel with others. GitHub is not a centralized system, you can also run it locally. Git has order without coordination. So no numerical progression.

A repository is the unit of seperation between in projects git.

Unix system ignore files with dot.
* Working directory; where you write
* Staging area; rough draft (git add)
* Repository; (git commit)

Status of repository with git status.
Git does not care about the content, it only tracks objects.  Git diff; working directory to staging area. Head of repository were we are currently area in local folder. 

Be selective of what you put in the staging area and commit. You can be selectie with git add. Don't mix commits. `git add .` is frowned upon.

When you change something in your working machine you don't copy it into the staging area. So they are not in sync.

## 2.1
Facebook for code. Adds social features on top of Git.

Adding remotes allows the transfer of commits to another machine. Cloud location. You can set a bookmark with `u` to set a default remote.

## 2.2
Fetch to get changes, looks at the remotes it transfers them locally. But this doesn't update the repo. Git only transmits the necessary objects.

## 2.3
Master is default branch. Newest commit is head. Fetch just grabbed the data. Git branch makes a new branch of the currently active commit. `tree .git/refs`

## 2.4
Pull = fetch and merge. Commits, puts them back together in the staging area and makes a new commits.

## 2.5
GitHub workflow scaled for the needs of students. Generate repo's.
* Assignment link; private repo with starter code.

Organizations can have multiple contributers. With each of their own permissions.

## 3.1 
Shared repository with starter code for group assignment.
Pull requests are for technically for merging one branch into the other. But they are also useful for peer feedback.
Hub package wraps git with extra cli commands.

Inline feedback can have canned responses, and you can also create issues.j

## 3.2
Git is very precise but it has a hard time if someone edit the same line. It needs a human to fix it.
* Conflict markers

## 3.3 / 3.4 
-

## 4.1
-