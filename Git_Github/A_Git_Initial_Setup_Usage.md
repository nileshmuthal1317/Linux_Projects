# Git and GitHub Lifecycle

## Setting up SSH Authentication
Generate the public and private keys and copy the public key and store it in the GitHub
```
ssh-keygen -t rsa -b 4096
```

## Installing the Git on CENTOS 8
```
sudo dnf install git
```
Configure the local user and email to identify the commits
```
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"
```
Create the new repository which can be push to GitHub
```
cd /path/to/your/directory
```
Initialize a new Git repository in that directory
```
git init
```
Add files to the repository
```
git add .
```
Commit your changes
```
git commit -m "Initial commit"
```
Connect your local repository to the GitHub repository
```
git remote add origin repository_url
```
Push your changes to GitHub
```
git push -u origin master
```
## Making further changes
Whenever you make changes to your project,

Stage the changes
```
git add .
```
Commit the changes
```
git commit -m "Your commit message"
```
Push the changes to GitHub
```
git push
```
You can pull the remote repository on your local 
```
git pull repository_url
```
