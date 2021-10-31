# Microphotonics
A collabrative latex program of Microphotonics in Ugent by Group 2 2021 semester.

# How to pull the remote repository into local
First you need a ssh key to establish links with my github account.
* Input `ssh-keygen -t rsa -C emailname@email.com` in terminal(replace emailname@email.com with your own email).
We don't need a password so tap enter key straightly util questions ending.
* `cat /Users/luwen/.ssh/id_rsa.pub` to print your ssh key.
* Copy what has shown at the last step and send it to me. I'll add your ssh key to my github acccount. 
Now you set a visiting link between your local computer and my github account.

Now let't pull the remote repository.
* The most important step in preparation: install git. After all you cannot make bricks without straw.
Please search tutorials by yourself on how to open and use it in MacOs or Windows. Or if you feel like having an insight
on how git works, you can refer to the official document version [git book](https://git-scm.com/book/en/v2).
The following codes will run in the terminal or git bash.
* `cd path`. Go to the path where you want to establish your local repository.
(Notice again that don't just put path but the real path in your computer like `cd /Users/luwen/dir`)
THe repository will be established under the last level file directory.
* `git clone -b master git@github.com:Tikilee/Microphotonics.git`. Now you clone the master branch of the remote repository.

# Basic operation of Git
* `git branch` View which branch you are in now.
  - `git branch -a` View all the branches, both remote and local included.
  - `git branch -r` View the remote branches.
  - `git branch -vv` View the correspondence between remote branches and local branches.
  - `git branch -d xx` Delete branch xx.
* `git status`
* Three-piece suit: `git add` `git commit` `git push` 
