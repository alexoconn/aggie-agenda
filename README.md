# aggie-agenda

***This README file contains a little bit about our goals for the project and some Git basics. I know it's a lot of information right now, but much of it will be used for reference if you are confused with something and need some basic instruction to jog your memory!

**This repository will be utilized to collaborate amongst each other and keep our source code in one place!!

--------------------------------------------------------------------------------------------------------------------------------
Goals:

-Getting a windows desktop application up and running. We will first create an application that prints out "Howdy World!"

-Getting a feel for Windows APIs and Calendar APIs

-Using the APIs to create a simple calendar interface on our desktop application.

-Making our calendar increasingly complex, such as adding different styles of time outlook (week at a glance, month at a glance) and functionalities that allow the user to type in events to be shown on the calendar.


Hopes (Not necessarily things we plan on achieving):

-Utilizing A&M databases to preinstall student schedules.

-Color coding different classes based upon the student's grade in those classes

**We will try to create a schedule that keeps us on track to meet our goals although it will not necessarily be binding. This IS a learning based project, and we all have classes to study for!!

-------------------------------------------------------------------------------------------------------------------------------------
If you have never used Git or GitHub before, here is some basic information and instruction: 


What's the Difference Between Git and GitHub?

Git is the actual version-control system. It allows you to save changes made to source files and also allows you to "upload" changes made by other members of your group onto the file you are presently working on. 

GitHub is really just an extension of Git. It's essentially a cloud or hosting service that can store local files remotely. GitHub will allow us to easily retrieve our project files that have been edited by someone in the group.


Basic Terminology:

Repository- This can be thought of as really just a folder. It stores all versions of the source files in an organized manner. The repository can either be local (the one on your computer) or remote (the one on github.com)

Commits- These are just saved versions of your code. This is analogous to clicking "save" when you are constructing a file.

Branches- These are where commits are stored.

So.... commits are stored in branches, and branches are stored in the repository. 


We will be using the command-line to work with Git and GitHub, so here are some of the commands (which will be given context later in the file)!:

git clone *url here*  --This will copy the remote repository onto your local computer

git status   -- This basically tells us the difference between our local repository files and remote repository files

git add  --Utilized basically anytime we create a new file or need to commit something

git commit  --This tells Git to create a snapshot of our current code and locks in the changes we have made to the source file on the local repository

git push  --This saves all of our local changes to the remote repository on GitHub

git pull --This retrieves changes made by other people back into your local repository

**Note: This is not an all-inclusive list but the most basic and prominently used commands. The step-by-step directions below introduce some more commands!!


Sooo, How Do I apply these commands?

Creating a Local Repository:
1. "Clone" the repository by clicking the "Clone or Download" button on the home page of the repository and copying the URL.

2. Use the git clone command in your command-line to store the repository in whatever folder you would like (If you don't know your command-line commands for your OS, please talk to us Project Managers or look them up online! No reason to fret!)


Creating a Branch and Adding Commits to it:

Remember, a branch is simply where commits (or saved versions of your code) are stored. There's a default master branch that serves as a history of all changes made to the project. However, we will be creating new branches anytime we want to start adding on to our project. We want to keep the master branch as concise as possible with commits we know we need and we know contain snapshots of code that function properly.

1. To create a branch, simply write the command: git branch "branch name".

2. To work within the branch, simply write: git checkout "branch name".

3. You can now create new files or add files to the branch. To do this, simply write: git add -A. This command will now allow Git to create commits for these files.

4. Whenever you have added files or have made changes to these files, simply write: git commit -m "message about the change you made". This will save the current version of the file(s) to your local repository. 

5. Once you have finished your branch, write: git push origin "local branch name" : "remote branch name" to transfer over your commits and branch to the remote repository.


Merging Branches/Pull Requests:

If your branch turned out successful, you now must merge your branch with the master branch so that your contributions to the project can be saved to the commit on the master branch. Remember, your branch was more of a test, and the master branch is the main copy of the project.

1. Submit a pull request. This will allow us to see the changes you've made and decide whether they should be added onto the main copy of the project. 

2. Once the pull request has been approved, write: git merge "branch name" to merge your branch to the master branch.

3. Delete your branch to keep the repository concise. Delete the branch in both your local and remote repository. The command to delete your local branch is git branch -d "local branch name". The command to delete a remote branch is git push origin --delete "branch name".
--------------------------------------------------------------------------------------------------------------------------------------
If you have any questions at any time, please do not hesitate to contact us project managers!

Additionally, here is are some links that might help you understand Git and GitHub better:
https://www.youtube.com/watch?v=0fKg7e37bQE --Walks you through the basic commands and explains the applications of them\

https://www.youtube.com/watch?v=GZILYABgAoo --Talks about branches, merging, and pull requests

https://docs.microsoft.com/en-us/cpp/windows/walkthrough-creating-windows-desktop-applications-cpp?view=vs-2019 -- Hello World Windows Desktop App
