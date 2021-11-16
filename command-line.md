# Command Line and Git

## Important Info:
* https://git-scm.com/
* https://gitforwindows.org/

## Most important commands in command line:

| Command | Meaning |
|:---:|:---|
| pwd | print current working directory |
| ls | list all files in directory |
| ls -l | list all files and their meta-data |
| ls -a | list all files, including hidden files |
| cd ~ | change directory to root |
| cd .. | go up one directory |
| cd ../.. | go up two directories |
| cd [name] | go down one directory (followed by directory name) |
| mkdir [name] | make a new directory (followed by directory name) |
| mv [oldname] [newname] | rename or move a file  |
| cp [oldname] [newname] | copy a file |
| cp -r [oldname] [newname] | copy a directory |
| rm [name] | remove a file |
| rm -rf [name] | remove a directory |
| * | a wildcard character, can be combined |  

## Git Commands:
| Command | Meaning |
|:---:|:---|
| git clone | brings down the repo to your laptop |
| git remote -v | shows the remote origin of the repo |
| git status | is your local repo behind the remote origin |
| git pull | updates the repo with latest changes |
| git add . | adds all your changes to the local repo |
| git commit -m "some message" | commits those changes to a branch |
| git push | adds your changes to the remote repo |

## Git Workflow:
![](https://res.cloudinary.com/hy4kyit2a/f_auto,fl_lossy,q_70/learn/projects/develop-app-with-salesforce-cli-and-source-control/add-salesforce-dx-project-to-source-control/images/bf546ec3acd964673bf5f6302125fd93_step-4-github-and-git-clones.png)

## Example of Branching:
![](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png)
