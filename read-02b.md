# GIT
**Types of version control** : 
1)  Local Version Control :  A Local VCS entails one database on your hard disk that stores changes to files.
 2) Centralized Version Control: This system entails a single server storing all changes and file versions, which can be accessed by various clients.
3) Distributed Version Control: If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. Also, in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
To prevent this type of catastrophic loss, a DVCS allows clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information.

**Useful features of Git**:
1) creating a snapshot of the file and stores a reference to it each time you save a changed version of your project.
2) relying on  local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk.
3) tracking changes
4) minimizing the possibility of irreversible damage to files, such as accidentally lost data 

**States on which GIT can reside**:
1) Committed
Data is securely stored in a local database
2) Modified
File has been changed but not committed to the database
3) Staged
Flagged a file’s changed version to be committed in the next snapshot


**Identify setting in GIT**:

After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.
Type the following into Terminal or Command Line:
git config --global user.name "Jane Smith"

git config --global user.email "example@email.com"
To confirm that you have the correct settings, enter the following command:
git config --global user.name (should return Jane Smith)

git config --global user.email (should return example@email.com)


**Importing files in GIT**:

1.	Switch to the target project’s directory
Example:
$ cd test (cd = change directory)
2.	Use the git init command
$ git init
Note: At this stage, you have created a new subdirectory named .git that has the repository files. Tracking has not commenced.
3.	To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”


**Workflow of GIT**

![GIT WORKFLOW](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)

**The life cycle of file status  in GIT**

![Life cycle of file status in GIT](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)
