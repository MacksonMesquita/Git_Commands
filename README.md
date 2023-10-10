# GitHub Commands <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" alt="Fire" width="40" />

**Language support:**

<p>
    <a href="/GitDocs/readme_fr.md">Français </a>
<p/> 
<p>
    <a href="/GitDocs/readme_es.md">Español</a>
<p/>
<p>
    <a href="/GitDocs/readme_pt-br.md">Português-BR</a>
<p/>
    
![](https://i.imgur.com/waxVImv.png)

* As you can see, the translations were done instantly, if there are any errors, please disregard the act
* If you like the content, share it

![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)

![](https://i.imgur.com/waxVImv.png)

<br/>
<br/>

## Introduction 👶

GitHub has a large repertoire of usable commands, which separately perform different functions. <br /> 
This repo will not introduce you to basic concepts about GitHub, it will just show you, some of the most used GitHub commands.

All commands visible in here, will be representing a function. Whether it's making a small commit or helping you handle branches.

<br/>

---

<br/>

### How make a commit 🐤

To make a commit there are a few steps.
<br />
First you must check if your repository has already been created on your GitHub.
<br />
It will already help you to do it, giving the first steps when creating a repo, however, here is a brief explanation of what each one does and represents.

##### For initializate your files on Git.
      git init

<br />
      
##### If you want to add a readme file.
      git add README.md

<br />

##### Making your commit with a message of your choice (it is worth remembering, that message will be displayed).
      git commit -m "first commit"

<br />

##### This command will help you to establish the necessary connection to upload your changes, note that this command synchronizes your local project with the repo present in your Git.
      git remote add origin https://github.com/YourUserName/YourRepoName.git

<br />

##### With this command, you can select the branch you want to upload the local content.
      git branch -M main

<br />

##### Do the push (as the name implies, _push_ is the act of pulling the local content, synchronized with your repo).
      git push -u origin main

<br />

Did you saw? It's not that difficult to commit and push in a repo, following these steps exactly, after creating a repo in your profile, you will upload all the available content to your GitHub!
It is important to remember that this is just the initial step, throughout a project, you will update it more often, and it is not necessary to repeat the process, just issue the following commands, and your new version will be available:

##### 
      git add . 
      git commit -m "update version"
      git push
      
<br />

### Visualization and manipulation 🙌

Here are some of the commands needed to view and manipulate branches and remote repositories:

#####
      1- git remote show origin
      2- git remote rename origin curso-git
      3 -git remote rm curso-git
      4- git remote -v
      5- git branch
      6- git checkout branchName
      7- git checkout master
      8- git merge branchName
      9- git branch -a
      10- git checkout -b NewBranch

**Respectively, they:**

* 1- Show the linked origin
* 2- Rename the linked origin
* 3- Remove the link to your repository
* 4- Show all linked origins
* 5- Display the branch you are manipulating
* 6- Select a branch of your choice
* 7- Return to the main branch
* 8- Merge your different branches
* 9- View all branches (both remote and local)
* 10- Create a new branch with the name of your choice

<br />

### Cloning a repo 👷

##### If you want clone an existing repo and use the files and stuff present in it, you can:
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

<br />

### File manipulation ✍️

You may at a given moment, want to change files present in your project, instead of looking for and changing it manually, you can:

#####
    1- git status
    2- git add file.txt
    3- git rm file.txt
    4- git rm directory 
    
**Respectively, the commands:**

* 1- Show the stats of your files in your directory
* 2- Add a file
* 3- Remove a file
* 4- Remove a directory

<br />

### Git pull 👇

Right now, if you know a little about git commands, you might be wondering why there is a single and exclusive session for the *git pull* command.
The answer is simple, the git pull command is not just a single command that executes an "any" function, it is perhaps the most used command after its brothers **commit and push**,
not to mention the countless variations and complements it has. So hold on, and let's do it!

<details>
<summary> What is the git pull command? </summary>
<br />
The git pull command is used to search and download content from remote repositories and immediately update the local repository so that the contents are the same, thus not having,
difference between the contents to be merged, without risk of errors or bugs.
<br />
<br />
In the first stage of the operation, git pull executes the git fetch command, which covers the local branch to which the HEAD points.
<br />
When the content is downloaded, git pull enters the merge workflow. The merge commit is created and the HEAD is updated to point to the new commit.
</details>

####
    git pull

<br />


## More useful commands 💻

#####
    1- git config --global user.email YourEmail
    2- git config --global user.name "Your name"
    3- git config --global core.excludesfile ~/.gitignore
    4- git help

**Respectively, the commands:**

* 1- Configures the user's global email (required during the git install process)
* 2- Configures the user's global name (required during the git install process)
* 3- Files to be ignored
* 4- The Git help 
