# GitHub Commands <img src="https://user-images.githubusercontent.com/74038190/212257468-1e9a91f1-b626-4baa-b15d-5c385dfa7ed2.gif" width="30">

**Language support:**

<p>
    <a href="/docs/readme_fr.md">Français </a>
    -- 
    <a href="/docs/readme_cn.md">繁體中文</a>
    --
    <a href="/docs/readme_es.md">Español</a>
    --
    <a href="/docs/readme_pt-BR.md">Português (Brasileiro)</a>
<p/>

*  As you can see, the translations were done instantly, if there are any errors, please disregard the act 🐱
---

### Introduction 👶

GitHub has a large repertoire of usable commands, which separately perform different functions. <br /> 
This repo will not introduce you to basic concepts about GitHub, it will just show you, some of the most used GitHub commands.

All commands visible in here, will be representing a function. Whether it's making a small commit or helping you handle branches.

---

### How make a commit 🐤

To make a commit there are a few steps, first you must check if your repository has already been created on your GitHub.
It will already help you to do it, giving the first steps when creating a repo, however, here is a brief explanation of what each one does and represents.

##### For initializate your files on Git.
      git init
      
##### If you want to add a readme file.
      git add README.md

##### Making your commit with a message of your choice (it is worth remembering, that message will be displayed).
      git commit -m "first commit"

##### This command will help you to establish the necessary connection to upload your changes, note that this command synchronizes your local project with the repo present in your Git.
      git remote add origin https://github.com/YourUserName/YourRepoName.git

##### With this command, you can select the branch you want to upload the local content.
      git branch -M main

##### Do the push (as the name implies, _push_ is the act of pulling the local content, synchronized with your repo).
      git push -u origin main

It saw? it's not that difficult to commit and push in a repo, following these steps exactly, after creating a repo in your profile, you will upload all the available content to your GitHub!
It is important to remember that this is just the initial step, throughout a project, you will update it more often, and it is not necessary to repeat the process, just issue the following commands, and your new version will be available:

##### 
      git add . 
      git commit -m "update version"
      git push
      

### Visualization and manipulation 🙌

Here are some of the commands needed to view and manipulate branches and remote repositories:

##### 
      git remote show origin
      git remote rename origin curso-git
      git remote rm curso-git
      git remote -v
      git branch
      git checkout branchName
      git checkout master
      git merge branchName

**Respectively, the commands:**

* Show the linked origin
* Renames the linked origin
* Unlink origin from git repository
* Shows the linked origin
* Shows the branch you are manipulating
* Switch from branch
* Goes back to the main branch
* Merge two different branches


### Cloning a repo 👷

##### If you want clone an existing repo and use the files and stuff present in it, you can:
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


### File manipulation ✍️

You may at a given moment, want to change files present in your project, instead of looking for and changing it manually, you can:

#####
    git status
    git add file.txt
    git rm file.txt
    git rm directory 
    
**Respectively, the commands:**

* Show the stats of your files in your directory
* Add a file
* Remove a file
* Remove a directory


## More useful commands 💻

#####
    git config --global user.email YourEmail
    git config --global user.name "Mackson Mesquita"
    git config --global core.excludesfile ~/.gitignore
    git help

**Respectively, the commands:**

* Configures the user's global email (required during the git install process)
* Configures the user's global name (required during the git install process)
* Files to be ignored
* The GitHub help 
