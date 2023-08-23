# GitHub Commands <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" alt="Fire" width="40" />

**Language support:**

<p>
    <a href="/GitDocs/readme_fr.md">Français </a>
<p/> 
<p>
    <a href="/GitDocs/readme_ch.md">繁體中文</a>
<p/> 
<p>
    <a href="/GitDocs/readme_es.md">Español</a>
<p/>
<p>
    <a href="/GitDocs/readme_pt-br.md">Português-BR</a>
<p/>

![](https://i.imgur.com/waxVImv.png)

* Comme vous pouvez voir, les traductions ont été faites instantanément, et peuvent contenir quelques erreurs, merci de ne pas de cet acte.
* Si vous aimez le contenu, partagez-le
  
![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)

![](https://i.imgur.com/waxVImv.png)

<br/>
<br/>

## Présentation 👶

GitHub dispose d'un large répertoire de commandes utilisables, chacune remplissant une fonction différente. <br />
Ce référentiel ne vous présentera pas les concepts de base de GitHub, il vous montrera simplement certaines des commandes GitHub les plus utilisées.

Chaque commande visible ici représentera une fonction, qu'elle soit chargée de faire un petit commit ou de vous aider à manipuler des branches.

<br/>

---

<br/>

### Comment faire un commit 🐤

Pour faire un commit, il y a quelques étapes. Tout d'abord, vous devez vous assurer qu'il existe un référentiel existant dans votre profil GitHub.
La même chose vous aidera déjà lorsque vous franchirez la première étape de la création d'un référentiel, mais quoi qu'il en soit, voici une petite explication de ce que chaque étape représente.

##### Pour initialiser vos fichiers dans Git.
      git init
      
##### Si vous souhaitez ajouter un fichier readme.
      git add README.md

##### Faire un commit avec un message de votre choix (rappelez-vous que ce message sera affiché).
      git commit -m "first commit"

##### Cette commande vous aidera à stabiliser la connexion nécessaire pour uploader vos modifications, notez que cette commande synchronise le dépôt local de votre projet avec celui présent sur votre GitHub.
      git remote add origin https://github.com/YourUserName/YourRepoName.git

##### Avec cette commande, vous pouvez sélectionner la branche dans laquelle vous souhaitez vider votre contenu.
      git branch -M main

##### Effectue le push (lorsque _push_ est dit, ce n'est rien de plus que l'acte d'extraire le contenu local, de le synchroniser et de le télécharger dans votre référentiel Git).
      git push -u origin main

Il a vu? Il n'est pas si difficile de valider et de pousser un référentiel, en suivant exactement ces étapes, une fois que vous avez créé le référentiel dans votre profil, vous aurez tout le contenu disponible !
Il est important de se rappeler que ce ne sont que les premières étapes, évidemment, tout au long de votre projet, vous le mettrez à jour plus souvent, cependant, il n'est pas nécessaire de répéter tout le processus, faites simplement certaines des étapes ci-dessous, et les nouvelles mises à jour sera disponible:

#####
      git add . 
      git commit -m "update version"
      git push


### Visualisation et manipulation 🙌

Voici quelques commandes nécessaires pour manipuler et afficher les branches et dépôts distants :

#####
      Git remote show origin
      git remote rename origin curso-git
      git remote rm curso-git
      git remote -v
      git branch
      git checkout branchName
      git checkout master
      git merge branchName
      git branch -a

**Respectivement, ils :**

* Afficher l'origine liée
* Renomme l'origine liée
* Supprime le lien vers votre référentiel
* Affiche toutes les origines liées
* Affichez la branche que vous manipulez
* Sélectionnez une succursale de votre choix
* Retourne à la branche principale
* Fusionnez vos différentes succursales
* Afficher toutes les succursales (à distance et locales)


### Cloner un dépôt 👷

##### Si vous souhaitez cloner un référentiel existant et utiliser les fichiers et le contenu qu'il contient, vous pouvez :
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


### Manipulation de fichiers ✍️

A un moment donné, vous aurez besoin de manipuler des fichiers, au lieu de le faire manuellement, vous pouvez le faire avec les commandes :

#####
    git status
    git add file.txt
    git rm file.txt
    git rm directory 

**Respectivement, les commandes :**

* Afficher l'état des fichiers présents dans votre répertoire
* Ajouter un fichier
* Supprimer un fichier
* Supprimer un répertoire


## Des commandes plus utiles 💻

#####
    git config --global user.email YourEmail
    git config --global user.name "Your name"
    git config --global core.excludesfile ~/.gitignore
    git help

**Respectivement, ils :**

* Configurer l'e-mail global de l'utilisateur (requis lors du processus d'installation de Git)
* Définissez le nom global de l'utilisateur (requis lors du processus d'installation de Git)
* Ignorez les fichiers de votre choix
* Afficher l'aide de Git
