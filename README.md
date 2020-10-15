# Github Commands v1.0

## Cloning a repository

1) Create a repository in github

2) Copy the URL Link of "Clone with SSH"

3) In VSCode terminal paste:
   git clone git@github.com:example/demo.git

4) Check for updated files:
    git status

5) Tracking the file
    git add "example.html" - If you need to track specific files
    git add. - If you want to track all the files

6) Commiting a file
    git commit -m "Added index.html" -m "Enter description here"

7) SSH (***Make sure to be in here bunao@DESKTOP-DE4FK5O MINGW64 by typing cd***)
    ssh-keygen -t rsa -b 4096 -C "bunao.peterandrei@gmail.com"
    Enter keyname: testkey

8) Searching for the key
   ls | grep testkey

9) Access the ssh key (Need to copy & paste to Github)
    cat testkey.pub

10) Update the files to the hosted repository
    git push origin master - The master can be main sometimes

## How to check for .git file in your folder

    ls -la

## Creating a fresh folder in a local directory (without .git file)

1) Putting .git file in the folder
    git init

2) Check for updated files:
    git status

3) Tracking the file
    git add "example.html" - If you need to track specific files
    git add. - If you want to track all the files

4) Commiting a file
   git commit -m "Added index.html" -m "Enter description here"

5) Create an empty repository

6) Copy the SSH link

7) Access the code on github
    git remote add origin url

8) Use git push in the future (-u means upstream)
    git push -u origin master 

9) Example