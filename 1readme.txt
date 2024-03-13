hello world
After installing GIT dsimulator on local cmachind we need to provide some usere information

git config --global user.email "email address"
git config --global user.name "user name"

The above associates you with the git account on GIT hub
To allow us work locally we can clone our Repository on github.com allowing us make a local copy
Cloning need to be done just once then we can do thinf link
Create a folder on your workstation -> right click and select "Open git Bash here"
This will open a terminal emulator
dapoa@DAPO-HOME MINGW64 /d/_Reponew
$ git --version
git version 2.44.0.windows.1
**** Above command show the version of GIT being used"

To copy the project in GITHUB.com we need to clone 
click the "code" button and copy the github link for your project
Got to you terminal emulator run "git clone https://github.com/Dapoawosika/MeLearnGit.git"

 dapoa@DAPO-HOME MINGW64 /d/_Reponew
$ git clone https://github.com/Dapoawosika/MeLearnGit.git

*** we obesrve output below***
Cloning into 'MeLearnGit'...
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 15 (delta 2), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (15/15), 4.84 KiB | 825.00 KiB/s, done.
Resolving deltas: 100% (2/2), done.

GO to the directory on the Windows and observe that all files have not been copied to the local PC later we will sync changes

Close the emulator and go to the directory on you local PC click in direcory and open with GIT emulator
You should see output below
********************************
dapoa@DAPO-HOME MINGW64 /d/_Reponew/MeLearnGit (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.
nothing to commit, working tree clean

****************************************************

We can create files
touch <file name>
********** note to allow GIT track the file wenn need to add and commit to the local Git hub

git add <file name>
The above entry flags the file to be tracked by Git ********* we also have to commit the file to git
git commit -m "add discription"
*******************************************
dapoa@DAPO-HOME MINGW64 /d/_Reponew/MeLearnGit (main)
$ git commit -m "addind file to Github"
[main d58615a] addind file to Github
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 4readme.txt
************************************************

git log

allow you see details oof wht is bring tracked by git

git push
Pushes the changes made on local machine to github.com

git fetch


git pull

git merge


