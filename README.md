# IECSE-App-Fall-22
Welcome to the IECSE App Fall Bootcamp 2022!
This repository contains all the resources and solutions to the tasks provided during the Fall project.

## Instructions - 
* We will be using [GitHub](https://github.com/geekyprawins/IECSE-App-Fall-22/wiki/Introduction-to-Git-&-Github) to accept and upload all your solutions to the tasks in the Fall project
* You will be creating your own branch to upload your solutions for the project
    * Create your own branch using the the command - `git checkout -b <branch-name>` and the `branch-name` should be in the format : `<first-name>-<last-name>`. For example: `git checkout -b Praveen-Varma`, here the `-b` tag is used to create a new branch.
* All commits should be made to your _own branch_. **Do not commit to main/master branch**. To prevent this always check what branch you're on before committing any changes, the command to check current branch git branch and/or command to checkout(change to) a branch, `git checkout <branch-name>`.
* Follow these steps to submit your solutions - 
    * Add all unstaged files using the command `git add .`. The `.` here means that all the files in the current directory will be staged/added to be committed.
    * To commit to your branch, use the following command: `git commit -m "Commit Message"`.   
      The format of the commit message should be as follows : `"Task #<task_no> : <task_description>`. Mention any errors or issues if any so that we can help you rectify them.
    * To finally push your code, use the following command: `git push origin <branch-name>`. If you are pushing your code for the first time, you will be prompted to provide your login details before you are able to push your code. If you are unable to push your code, contact your domain head.
* To pull the solutions to the task, use the following commands :   
    ```Bash
    git checkout master
    git pull origin master
    ```

* An example of how this will look :   
```Bash
git checkout -b Praveen-Varma
git checkout Praveen-Varma        //to check if you are still in your own branch
git add .                           //stage all the files in the directory for commit
git commit -m "Task #00: Description"
git push origin Praveen-Varma     //this pushes the code to your own branch
```
* All the solutions will be posted in the master branch.

* All the tasks and resources for the summer project will be posted in the [Wiki](https://github.com/geekyprawins/IECSE-App-Fall-22/wiki).
