[React Tutorial for Beginners](https://www.youtube.com/watch?v=0ByoQm-vnYw)

[devslopes is dubious](https://github.com/devslopes/react-skeleton)

~~~
open Ubuntu on Windows 10
allan@SAMSON:~$
allan@SAMSON:~$ cd /mnt/d/code/sandbox/
allan@SAMSON:/mnt/d/code/sandbox$

from chrome navigate: https://github.com/AllanRevenig

	create repo: "react-skeleton"
	no README.md

	copy repo name: https://github.com/AllanRevenig/react-skeleton

$ mkdir react-skeleton
$ cd react-skeleton
$ git init
  >>> oops, unable to resolve host SAMSON
  >>> run: sudo apt-get install git
$ sudo apt-get install git
$ git init
  >>> Initialized empty Git repository in /mnt/d/code/sandbox/react-skeleton/.git/
allan@SAMSON:/mnt/d/code/sandbox/react-skeleton$ ls -al
total 9
drwxrwxrwx 2 root root   0 Jan 28 18:41 .
drwxrwxrwx 2 root root   0 Jan 28 18:35 ..
drwxrwxrwx 2 root root   0 Jan 28 18:46 .git
-rwxrwxrwx 1 root root 656 Jan 28 18:46 react-tutorial-for-beginners.txt

allan@SAMSON:/mnt/d/code/sandbox/react-skeleton$ git remote add origin https://github.com/AllanRevenig/react-skeleton


going forward using $$ as a shortcut for this:allan@SAMSON:/mnt/d/code/sandbox/react-skeleton$
or if a git repo: $(branch)$


$$ touch README.md

$$ git status
On branch master
Initial commit
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.md
        new file:   react-tutorial-for-beginners.txt

allan@SAMSON:/mnt/d/code/sandbox/react-skeleton$ git commit -m 'add readme and notes files'

*** Please tell me who you are.
Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.
fatal: unable to auto-detect email address (got 'allan@SAMSON.(none)')


$$ git config --global user.email "allanr@msn.com"
$$ git config --global user.name "Allan Revenig"

$$ git commit -m 'add readme and notes files'
[master (root-commit) e0777e9] add readme and notes files
 2 files changed, 31 insertions(+)
 create mode 100644 README.md
 create mode 100644 react-tutorial-for-beginners.txt

$allan@SAMSON:/mnt/d/code/sandbox/react-skeleton (master)$
  >>> note (master) now shows up on my .bashrc command-line configuration!!!

$$ git push origin master

Username for 'https://github.com': allanr@msn.com
Password for 'https://allanr@msn.com@github.com':
Counting objects: 4, done.
Delta compression using up to 8 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 715 bytes | 0 bytes/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/AllanRevenig/react-skeleton
 * [new branch]      master -> master

$(master)$

$$ npm install -g browserify
  >>> maybe do this locally as well
      (won't always use this, but webpack instead)
$$ npm install --save babelify
$$ npm install --save watchify
$$ npm install --save babel-preset-react
$$ npm install --save react react-dom


https://zellwk.com/blog/gitignore/
add this to .gitignore for windows


# Windows thumbnail cache files
Thumbs.db
ehthumbs.db
ehthumbs_vista.db

# Folder config file
Desktop.ini

# Recycle Bin used on file shares
$RECYCLE.BIN/

# Windows Installer files
*.cab
*.msi
*.msm
*.msp

# Windows shortcuts
*.lnk

$$
