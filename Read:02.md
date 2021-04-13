# Setting up a Git Repository

after you sign up in git hub you should create up a repository to your work 
to start the work.

### Local Repository Structure
1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit

![img](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

### Saving Changes

1. Tracked
Tracked files can be modified, unmodified, or staged; they were part of the most recent file snapshot.

2. Untracked
Untracked files were not in the last snapshot and do not currently reside in the staging area.
After cloning a repository, files have tracked status and are unmodified because they have been checked out but not edited.

### Tracking and Staging a New File

1. Single File
  - Track one file only by using the following format:

 > git add filename

2. All Files
 - Track all files in a repository by using the following command:

 > $ git add *

### Stashing Changes

When you are not ready to commit changes but do not want to lose them either, git stash is a great option. 
This command temporarily removes changes and hides them, giving you a clean working directory. 
When you are ready to continue working on the changes, simply use the git stash apply command to retrieve the hidden changes.

### Remote Repositories

In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. 
You can work with multiple repositories, for which you can have read/write or read-only privileges. 
Teams can use remote repositories to push information to and pull data from.

1. Seeing Your Remotes

By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.
By using git remote -v, you can view all the remote URLs next to their corresponding short names.
