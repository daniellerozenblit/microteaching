# Git Workshop Cheat Sheet

## Bash Commands

### cd

cd is short for change directories, which essentially means changing the folder you are in. To use it, type: `cd <file_path_you_want_to_switch_to`

### ls

ls lists all of the files within your current directory. To use it, type: `ls`

### pwd

pwd tells you your current directory. To use it, type: `pwd`

### rm

rm removes a file. However, if you are in a repository, use git rm so you can track the fact you removed that file. To use these, type: `rm <file_path_to_file_to_delete>` or `git rm <file_path_to_file_to_delete>`

## Git Commands

### git status

git status tells you the files that are untracked or are added and ready to commit. Useful if you forget which files you have added! To use it, type: `git status`

### branching

#### git branch

Tells you the current branch you are on. To use it, type: `git branch`

#### git checkout

Lets you move from one branch to another. To use it, type: `git checkout <branch_name_you_are_switching_to>`

#### git branch -b

Lets you create a new branch. Make sure you are doing this from the main branch so you aren't accidentally creating a sub-branch! To use it, type: `git branch -b <new_branch_name>`

### git stash

Sometimes, you want to move branches without committing your changes. git stash lets you store the changes until later. To use it, type: `git stash <file_name>`

### committing changes

#### git add

First, to commit changes and make a pull request, you need to add which files you have changed/added. You can add folders or individual files. To use it, type: `git add <file_path_1> <file_path_2> ... <file_path_n>`

#### git commit

Next, you need to commit your changes. You can also add a message to say what you have changed. To use it without a message, type: `git commit` after you add your changes. To add a message, type: `git commit -m "message body`

#### git push

Finally, to push your changes to the repository, type `git push` If this is your first time pushing on this branch, it will have you type in a slightly different command that you can copy and paste. Once you run that, it will give you a url which you can use to make your PR
