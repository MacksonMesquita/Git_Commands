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

* Como puede ver, las traducciones se realizaron al instante y pueden contener algunos errores, ignore este acto.
* Si te gusta el contenido compártelo

![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)
![Discord](https://img.shields.io/badge/Discord-%235865F2.svg?style=for-the-badge&logo=discord&logoColor=white)
![Facebook](https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)
![Twitter](https://img.shields.io/badge/Twitter-%231DA1F2.svg?style=for-the-badge&logo=Twitter&logoColor=white)

![](https://i.imgur.com/waxVImv.png)

<br/>
<br/>

## introducción 👶

GitHub tiene un gran repertorio de comandos utilizables y cada uno realiza una función diferente. <br />
Este repositorio no le presentará los conceptos básicos de GitHub, solo le mostrará algunos de los comandos de GitHub más utilizados.

Cada comando visible aquí representará una función, ya sea responsable de realizar una pequeña confirmación o de ayudarlo a manipular ramas.

<br/>

---

<br/>

### Cómo hacer un commit 🐤

Para hacer un commit hay algunos pasos. 
<br />
Primero, debe asegurarse de que exista un repositorio en su perfil de GitHub.
<br />
Lo mismo ya te ayudará cuando des el primer paso creando un repositorio, pero de todos modos aquí te dejamos una pequeña explicación de lo que representa cada paso.

##### Para inicializar sus archivos en Git.
      git init

<br />
      
##### En caso de que desee agregar un archivo readme.
      git add README.md

<br />

##### Haciendo un commit con un mensaje de tu elección (vale la pena recordar que este mensaje será desplegado).
      git commit -m "first commit"

<br />

##### Este comando lo ayudará a estabilizar la conexión necesaria para sus cambios, tenga en cuenta que este comando sincroniza el repositorio local de su proyecto con el presente en su GitHub.
      git remote add origin https://github.com/YourUserName/YourRepoName.git

<br />

##### Con este comando, puede seleccionar la rama en la que desea volcar su contenido.
      git branch -M main

<br />

##### Realiza el push (cuando se dice _push_, no es más que el acto de extraer el contenido local, sincronizarlo y subirlo a tu repositorio Git).
      git push -u origin main

<br />

¿Vio? No es tan difícil comprometer y empujar un repositorio, siguiendo estos pasos al pie de la letra, una vez que hayas creado el repositorio en tu perfil, ¡tendrás todo el contenido disponible!
Es importante recordar que estos son solo los pasos iniciales, obviamente, a lo largo de su proyecto, lo actualizará con más frecuencia, sin embargo, no es necesario repetir todo el proceso, solo realice algunos de los pasos a continuación y las nuevas actualizaciones estará disponible:

##### 
      git add . 
      git commit -m "update version"
      git push

<br />

### visualización y manipulación 🙌

Aquí hay algunos comandos necesarios para manipular y ver sucursales y repositorios remotos:

##### 
      git remote show origin
      git remote rename origin curso-git
      git remote rm curso-git
      git remote -v
      git branch
      git checkout branchName
      git checkout master
      git merge branchName
      git branch -a

**Respectivamente, ellos:**

* Mostrar el origen vinculado
* Cambia el nombre del origen vinculado
* Elimina el enlace a su repositorio
* Muestra todos los orígenes vinculados
* Muestra la rama que estás manipulando.
*Seleccione una sucursal de su preferencia
*Vuelve a la sucursal principal
* Fusiona tus diferentes sucursales
* Ver todas las sucursales (tanto remotas como locales)

<br />

### Clonar un repositorio 👷

##### Si desea clonar un repositorio existente y usar los archivos y contenidos presentes, tu puede:
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

<br />

### Manipulación de archivos ✍️

En algún momento necesitará manipular archivos, en lugar de hacerlo manualmente, puede hacerlo con los comandos:

#####
    git status
    git add file.txt
    git rm file.txt
    git rm directory

**Respectivamente, los comandos:**

* Mostrar el estado de los archivos presentes en su directorio
* Añadir un archivo
* Eliminar un archivo
* Eliminar un directorio

<br />

## Comandos útiles 💻

#####
    git config --global user.email YourEmail
    git config --global user.name "Your name"
    git config --global core.excludesfile ~/.gitignore
    git help

**Respectivamente, sirven para:**

* Configurar el correo electrónico global del usuario (requerido durante el proceso de instalación de Git)
* Establecer el nombre global del usuario (requerido durante el proceso de instalación de Git)
* Ignorar archivos de su elección
* Mostrar la ayuda de Git
