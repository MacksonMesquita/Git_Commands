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
<p>
    <a href="/README.md">English</a>
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
      1-Git remote show origin
      2- git remote rename origin curso-git
      3- git remote rm curso-git
      4- git remote -v
      5- git branch
      6- git checkout branchName
      7- git checkout master
      8- git merge branchName
      9- git branch -a
      10- git checkout -b NewBranch

**Respectivement, ils :**

* 1- Afficher l'origine liée
* 2- Renomme l'origine liée
* 3- Supprime le lien vers votre référentiel
* 4- Affiche toutes les origines liées
* 5- Affichez la branche que vous manipulez
* 6- Sélectionnez une succursale de votre choix
* 7- Retourne à la branche principale
* 8- Fusionnez vos différentes succursales
* 9- Afficher toutes les succursales (à distance et locales)
* 10- Créez une nouvelle branche avec le nom de votre choix


### Cloner un dépôt 👷

##### Si vous souhaitez cloner un référentiel existant et utiliser les fichiers et le contenu qu'il contient, vous pouvez :
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


### Manipulation de fichiers ✍️

A un moment donné, vous aurez besoin de manipuler des fichiers, au lieu de le faire manuellement, vous pouvez le faire avec les commandes :

#####
    1- git status
    2- git add file.txt
    3- git rm file.txt
    4- git rm directory 

**Respectivement, les commandes :**

* 1- Afficher l'état des fichiers présents dans votre répertoire
* 2- Ajouter un fichier
* 3- Supprimer un fichier
* 4- Supprimer un répertoire

<br />

### Git pull 👇

À l'heure actuelle, si vous connaissez un peu les commandes git, vous vous demandez peut-être pourquoi il existe une session unique et exclusive pour la commande *git pull*.
La réponse est simple, la commande git pull n'est pas qu'une simple commande qui exécute une fonction "n'importe laquelle", c'est peut-être la commande la plus utilisée après ses frères **commit et push**,
sans parler des innombrables variantes et compléments dont il dispose. Alors attendez et faisons-le !

<details>
<summary> Qu'est-ce que la commande git pull ? </summary>
<br />
La commande git pull est utilisée pour rechercher et télécharger du contenu à partir de référentiels distants et mettre immédiatement à jour le référentiel local afin que le contenu soit le même, sans avoir,
différence entre les contenus à fusionner, sans risque d'erreurs ou de bugs.
<br />
<br />
Dans la première étape de l'opération, git pull exécute la commande git fetch, qui couvre la branche locale vers laquelle pointe HEAD.
<br />
Lorsque le contenu est téléchargé, git pull entre dans le workflow de fusion. La validation de fusion est créée et le HEAD est mis à jour pour pointer vers la nouvelle validation.
</details>

####
     git pull

<br />

## Des commandes plus utiles 💻

#####
    1- git config --global user.email YourEmail
    2- git config --global user.name "Your name"
    3- git config --global core.excludesfile ~/.gitignore
    4- git help

**Respectivement, ils :**

* 1- Configurer l'e-mail global de l'utilisateur (requis lors du processus d'installation de Git)
* 2- Définissez le nom global de l'utilisateur (requis lors du processus d'installation de Git)
* 3- Ignorez les fichiers de votre choix
* 4- Afficher l'aide de Git
