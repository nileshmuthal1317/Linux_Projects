# Git and GitHub Initial Setup and Working

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

## Create the new repository which can be push to GitHub

Go to your workspace folder
```
cd /path/to/your/repository
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

## Working with GitHub repository locally and pushing the changes to remote repository

Clone the repository
```
git clone Repo_URL
```
Pull or sync remote repostory data with local repository
```
gut pull
```
Once you update the any file in repository you can Stage the changes
```
git add .
```
Check the status and log of changes
```
git status
```
```
git log
```
Commit the changes
```
git commit -m "Your commit message"
```
Push the changes to GitHub
```
git push
```

