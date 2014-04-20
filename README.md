This is a test file for git tutorial.
git init - create a new repo in current dir[note: current dir is a repo now]
git add <filename> - add <filename> to the staging area[index]
git clone /path/to/repo - clone a local repo to current repo.
git clone username@host:/path/to/repo - clone a remote repo to current dir.
git config --global user.name "dongshichao"
git config --global user.email "dongshichao1988@gmail.com"
git commit --amend --reset-author
git reset HEAD <file> - to unstage
<<<<<<< HEAD
git checkout -- <filename> to discard changes in working directory before add.

git push origin <branch> - to push committed changes to remote repo.
git commit -m "message" - commit changes to HEAD.

ALOHAALOHAALOHAALOHAALOHAALOHAALOHAALOHA
=======
git checkout -- <filename> to discard changes in working directory

git checkout -b <new_branch> - create a new branch and switch to it
git rm --cached <filename> - remove <filename> from staging area, not working tree.
 
>>>>>>> dev
