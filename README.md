# WELCOME TO THE INTRODUCTION OF THE GIT
To create a repository you gotta write this in git bash
```bash
git init
```
That allows you to create a new directory which is actually your git repository

## Creating a new files
To create a new file use:
```bash
touch <nameofFile>.type
```
But before make sure that you're at the directory you want to create a file to

## Initialization
Use this commands to add and commit your files
```bash
git add --all
git commit -m "My first commit"
```
That allows you to eventually commit changes

### SSH-key
To have an access to your remote repository you need to:
1. Create a SSH-key
2. Tie your key with the remote repository
---
```bash
ssh-keygen -t ed25519 -C "your email that's connected to GitHub"
clip < ~/.ssh/id_ed25519.pub
```
And now just paste it to GitHub to work without obstacles

### Connecting local repository with remote repository
To connect you gotta:
```bash
git remote add origin git@github.com:%name-of-your-account%/your-project.git
```
After commits just push all the changes to the remote repository
```bash
git push -u origin main
```
Just make sure you print -u for the first time, you don't need to print it all the time. Next time write just "git push"
### README File
Read a little bit about README file to know how to write about your projects to other people
[README](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/ "Yandex Practicum documentation") or just use [README-2](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c "GitHub documentation")