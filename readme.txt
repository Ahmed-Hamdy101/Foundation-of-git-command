git branch -m master main
git fetch origin
git branch -u origin/main main
git remote set-head origin -a

----------------------------------------------------------------------------------------------------------
error faild logon // updates git
 git update-git-for-windows

------------------------------------------------------------------------------------------------------------

echo "# git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:Turria101/Laravel-Blog-Project.git
git push -u origin master


-- my tutorial


 ls
ch01/  ch02/  ch03/  ch04/






-----------------------------------------------------------------------------------------------------------------------
-Electron-@Black-Gate2 MINGW64 ~/Documents/git
$ git init
Initialized empty Git repository in C:/Users/-Electron-/Documents/git/.git/

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git add *
warning: in the working copy of 'ch01/git_add.sh', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch01/git_commit.sh', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch01/git_different.sh', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch01/git_state.sh', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch02/.gitignore', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch03/git_commit.sh', LF will be replaced by CRLF the next time Git touches it
warning: in the working copy of 'ch04/git_config_list.sh', LF will be replaced by CRLF the next time Git touches it

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git add .

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   ch01/git_add.sh
        new file:   ch01/git_commit.sh
        new file:   ch01/git_different.sh
        new file:   ch01/git_state.sh
        new file:   ch02/.gitignore
        new file:   ch02/example.php
        new file:   ch02/gitignore.txt
        new file:   ch03/git_commit.sh
        new file:   ch04/git_config_list.sh


-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git commit -m "master"
[master (root-commit) 0eb6db3] master
 9 files changed, 38 insertions(+)
 create mode 100644 ch01/git_add.sh
 create mode 100644 ch01/git_commit.sh
 create mode 100644 ch01/git_different.sh
 create mode 100644 ch01/git_state.sh
 create mode 100644 ch02/.gitignore
 create mode 100644 ch02/example.php
 create mode 100644 ch02/gitignore.txt
 create mode 100644 ch03/git_commit.sh
 create mode 100644 ch04/git_config_list.sh

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ echo "# git Tutorial" >> README.md

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git add README.md
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git branch -M master

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git remote add origin git@github.com:Turria101/Tweets-Project.git

-Electron-@Black-Gate2 MINGW64 ~/Documents/git (master)
$ git push -u origin master
Enter passphrase for key '/c/Users/-Electron-/.ssh/id_ed25519':
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (15/15), 1.16 KiB | 238.00 KiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:Turria101/git.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

