# Introduction to GitHub Commands

GitHub is very much popular web-based application in current industry for hosting variety services targeting version control using GIT commands. It offers various distributed version controlling as well as source code management properly.
 
1. git config 
2. git init
3. git clone
4. git add
5. git commit
6. git diff
7. git reset
8. git status
9. git rm
10. git log
11. git show
12. git tag
13. git branch
14. git checkout
15. git merge
16. git remote
17. git push
18. git pull
19. git stash

# git config
Usage: git config –global user.name “[name]”  
Usage: git config –global user.email “[email address]”  
This command sets the author name and email address respectively to be used with your commits.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/1-9.png)

# git init
Usage: git init [repository name]
This command is used to start a new repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/2-6.png)

# git clone
Usage: git clone [url]  
This command is used to obtain a repository from an existing URL.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/4-4.png)

# git add
Usage: git add [file]  
This command adds a file to the staging area.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/5-4.png)

Usage: git add *  
This command adds one or more to the staging area.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/6-3.png)

# git diff
Usage: git diff  
This command shows the file differences which are not yet staged.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/9-2.png)\

Usage: git diff –staged 
This command shows the differences between the files in the staging area and the latest version present.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/10-2.png)

Usage: git diff [first branch] [second branch]  
This command shows the differences between the two branches mentioned.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/43.png)

# git reset
Usage: git reset [file]  
This command unstages the file, but it preserves the file contents.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/11-1.png)

Usage: git reset [commit]  
This command undoes all the commits after the specified commit and preserves the changes locally.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/14-1.png)

Usage: git reset –hard [commit]  This command discards all history and goes back to the specified commit.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/13-1.png)

# git status
Usage: git status  
This command lists all the files that have to be committed.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/15-1.png)

# git rm
Usage: git rm [file]  
This command deletes the file from your working directory and stages the deletion.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/16-2.png)

# git log
Usage: git log  
This command is used to list the version history for the current branch.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/18.png)

Usage: git log –follow[file]  
This command lists version history for a file, including the renaming of files also.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/19.png)

# git show
Usage: git show [commit]  
This command shows the metadata and content changes of the specified commit.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/20.png)

# git tag
Usage: git tag [commitID]  
This command is used to giv
e tags to the specified commit.
![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/22.png])

# git branch
Usage: git branch  
This command lists all the local branches in the current repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/23.png)

Usage: git branch [branch name]  
This command creates a new branch.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/24.png)

Usage: git branch -d [branch name]  
This command deletes the feature branch.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/25.png)

# git checkout
Usage: git checkout [branch name]  
This command is used to switch from one branch to another.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/27.png)

Usage: git checkout -b [branch name]  
This command creates a new branch and also switches to it.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/28.png)

# git merge
Usage: git merge [branch name]  
This command merges the specified branch’s history into the current branch.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/31-1.png)

# git remote
Usage: git remote add [variable name] [Remote Server Link]  
This command is used to connect your local repository to the remote server.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/32.png)

# git push
Usage: git push [variable name] master  
This command sends the committed changes of master branch to your remote repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/33.png)

Usage: git push [variable name] [branch]  
This command sends the branch commits to your remote repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/34.png)

Usage: git push –all [variable name]  
This command pushes all branches to your remote repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/36.png)

Usage: git push [variable name] :[branch name]  
This command deletes a branch on your remote repository.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/37.png)

# git pull
Usage: git pull [Repository Link]  
This command fetches and merges changes on the remote server to your working directory.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/38.png)

# git stash
Usage: git stash save  
This command temporarily stores all the modified tracked files.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/39.png)

Usage: git stash pop  
This command restores the most recently stashed files.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/40.png)

Usage: git stash list  
This command lists all stashed changesets.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/44.png)

Usage: git stash drop  
This command discards the most recently stashed changeset.

![](https://d1jnx9ba8s6j9r.cloudfront.net/blog/wp-content/uploads/2018/07/42.png)

## Main porcelain commands

git-add[1]
Add file contents to the index

git-am[1]
Apply a series of patches from a mailbox

git-archive[1]
Create an archive of files from a named tree

git-bisect[1]
Use binary search to find the commit that introduced a bug

git-branch[1]
List, create, or delete branches

git-bundle[1]
Move objects and refs by archive

git-checkout[1]
Switch branches or restore working tree files

git-cherry-pick[1]
Apply the changes introduced by some existing commits

git-citool[1]
Graphical alternative to git-commit

git-clean[1]
Remove untracked files from the working tree

git-clone[1]
Clone a repository into a new directory

git-commit[1]
Record changes to the repository

git-describe[1]
Give an object a human readable name based on an available ref

git-diff[1]
Show changes between commits, commit and working tree, etc

git-fetch[1]
Download objects and refs from another repository

git-format-patch[1]
Prepare patches for e-mail submission

git-gc[1]
Cleanup unnecessary files and optimize the local repository

git-grep[1]
Print lines matching a pattern

git-gui[1]
A portable graphical interface to Git

git-init[1]
Create an empty Git repository or reinitialize an existing one

gitk[1]
The Git repository browser

git-log[1]
Show commit logs

git-maintenance[1]
Run tasks to optimize Git repository data

git-merge[1]
Join two or more development histories together

git-mv[1]
Move or rename a file, a directory, or a symlink

git-notes[1]
Add or inspect object notes

git-pull[1]
Fetch from and integrate with another repository or a local branch

git-push[1]
Update remote refs along with associated objects

git-range-diff[1]
Compare two commit ranges (e.g. two versions of a branch)

git-rebase[1]
Reapply commits on top of another base tip

git-reset[1]
Reset current HEAD to the specified state

git-restore[1]
Restore working tree files

git-revert[1]
Revert some existing commits

git-rm[1]
Remove files from the working tree and from the index

git-shortlog[1]
Summarize git log output

git-show[1]
Show various types of objects

git-sparse-checkout[1]
Initialize and modify the sparse-checkout

git-stash[1]
Stash the changes in a dirty working directory away

git-status[1]
Show the working tree status

git-submodule[1]
Initialize, update or inspect submodules

git-switch[1]
Switch branches

git-tag[1]
Create, list, delete or verify a tag object signed with GPG

git-worktree[1]
Manage multiple working trees

## Ancillary Commands
*Manipulators:*

git-config[1]
Get and set repository or global options

git-fast-export[1]
Git data exporter

git-fast-import[1]
Backend for fast Git data importers

git-filter-branch[1]
Rewrite branches

git-mergetool[1]
Run merge conflict resolution tools to resolve merge conflicts

git-pack-refs[1]
Pack heads and tags for efficient repository access

git-prune[1]
Prune all unreachable objects from the object database

git-reflog[1]
Manage reflog information

git-remote[1]
Manage set of tracked repositories

git-repack[1]
Pack unpacked objects in a repository

git-replace[1]
Create, list, delete refs to replace objects

Interrogators:

git-annotate[1]
Annotate file lines with commit information

git-blame[1]
Show what revision and author last modified each line of a file

git-bugreport[1]
Collect information for user to file a bug report

git-count-objects[1]
Count unpacked number of objects and their disk consumption

git-difftool[1]
Show changes using common diff tools

git-fsck[1]
Verifies the connectivity and validity of the objects in the database

git-help[1]
Display help information about Git

git-instaweb[1]
Instantly browse your working repository in gitweb

git-merge-tree[1]
Show three-way merge without touching index

git-rerere[1]
Reuse recorded resolution of conflicted merges

git-show-branch[1]
Show branches and their commits

git-verify-commit[1]
Check the GPG signature of commits

git-verify-tag[1]
Check the GPG signature of tags

gitweb[1]
Git web interface (web frontend to Git repositories)

git-whatchanged[1]
Show logs with difference each commit introduces

Interacting with Others
These commands are to interact with foreign SCM and with other people via patch over e-mail.

git-archimport[1]
Import a GNU Arch repository into Git

git-cvsexportcommit[1]
Export a single commit to a CVS checkout

git-cvsimport[1]
Salvage your data out of another SCM people love to hate

git-cvsserver[1]
A CVS server emulator for Git

git-imap-send[1]
Send a collection of patches from stdin to an IMAP folder

git-p4[1]
Import from and submit to Perforce repositories

git-quiltimport[1]
Applies a quilt patchset onto the current branch

git-request-pull[1]
Generates a summary of pending changes

git-send-email[1]
Send a collection of patches as emails

git-svn[1]
Bidirectional operation between a Subversion repository and Git


