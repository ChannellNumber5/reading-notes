# An Overview of Version Control Systems a.k.a git

Before formally summarizing what I've learned in this module's reading, I figured that I would explain what Version Control Systems (VCS) are, in my own words - which were inspired by course lecture 3 and "Git Tutorial: A Comprehensive Guide". 

Essentially, a VCS is exactly what its name suggests, its a way of controlling various "copies" of the file that you are working on or working with. This is incredibly important as developers are working on a project because it allows for easy access to previous versions of files as well as creating a back up for the files that developers are working with. 

The main components of a VCS is the system itself and then the developers personal platform/computer. In order to work on a file, the developer would download the file from the system, work on it and then upload it back on to the VCS. Once the changed file is uploaded, the VCS tracks that a change has been made and also keeps a version of the older file.

## Now for the Code behind git and Making Changes to Repositories on github
When working in the terminal, the developer will need to clone their repository from github onto their desktop using the `git clone #insert repository link command`.

Once you have cloned your repository from github, you'll need to change directories to your repository using the `cd #insert repository name command 

Then you will need to open up your code in VS Code (assuming that VS Code is the Text Editor that you have chosen to use). To open it in VC Code, use the command `code . ` which was configured to open VS Code. The `.` part of the command opens all of the files within the directory of your repository

Once you've made changes in VS Code, you'll then need to use teh ACP process in order to "upload" your changes to github. Here is the ACP process:

    - A: stands for add, where you will use the `git add .` command which "stages" all of the files in your repository, so that the changes can be committed. If you choose not to use `.` you can specify which file you'd like to stage to be "uploaded"

    - C: stands for commit, where you will use the `git commit -m ""` command, where you will commit your changes. The `-m` is used to create your "commit message" which is a PUBLIC message that tracks the changes that you are making to the files in your repository.
    
    - P: stands for push, where you will use the `git push orgin main` command to push your commits to github.

    Do note that in this process, you will want to use the `git status` command to track where your files are at in the process. The status command will tell you what "version" your repository and its files are on and what changes are pending to be committed.