# GitHub Commands <img src="https://user-images.githubusercontent.com/74038190/216122041-518ac897-8d92-4c6b-9b3f-ca01dcaf38ee.png" alt="Fire" width="40" />

**Language support:**

<p>
    <a href="/GitDocs/readme_fr.md">Français </a>
    . 
    <a href="/GitDocs/readme_ch.md">繁體中文</a>
    .
    <a href="/GitDocs/readme_es.md">Español</a>
    .
    <a href="/GitDocs/readme_pt-br.md">Português-BR</a>
<p/>

* Como você pode ver, as traduções foram feitas instântaneamente, e podem conter alguns erros, por favor, desconsidere tal ato.
---

### Introdução 👶

O GitHub tem um grande repertório de comandos utilizáveis, e cada um, realiza uma função diferente. <br />
Este repositório não introduzirá você a conceitos básicos do GitHub, ele apenas te mostrará, alguns dos comandos mais utilizados do mesmo.

Todo comando visivel aqui, representará uma função, seja ela responsável por fazer um pequeno commit ou ajudar você a manipular branches.

---

### Como fazer um commit 🐤

Para fazer um commit existem algumas etapas. Primeiro, você deve certificar que há um repositório existente em seu perfil no GitHub.
O mesmo, já irá te ajudar quando você der o primeiro passo criando um repositório, mas de qualquer maneira, aqui vai uma pequena explicação do que cada passo dado representa.

##### Para inicializar seus arquivos no Git.
      git init
      
##### Caso você queira adicionar um arquivo readme.
      git add README.md

##### Fazendo um commit com uma menssagem de sua escolha (vale lembrar que esta menssagem será exibida).
      git commit -m "first commit"

##### Este comando ajudará você a estabilizar a conexão necessária para subir suas alterações, note que este comando sincroniza o repositório local do seu projeto com o presente em seu GitHub.
      git remote add origin https://github.com/YourUserName/YourRepoName.git

##### Com este comando, você pode selecionar a branch que deseja despejar seu conteudo.
      git branch -M main

##### Realiza o push (quando se diz _push_, nada mais é do que o ato de puxar o conteudo local, sincroniza-lo e subi-lo em seu repositório Git).
      git push -u origin main

Viu? Não é tão difícil commitar e realizar um push em um repositório, seguindo exatamente estas etapas, depois de ter criado o repositório em seu perfil, você terá todo o conteúdo disponível!
É importante lembrar que estes são apenas os passos iniciais, obviamente, ao longo de seu projeto, você o atualizará mais vezes, entretanto, não é necessário repetir todo processo, apenas faça alguns dos passos abaixo, e as novas atualizações estarão disponíveis:

##### 
      git add . 
      git commit -m "update version"
      git push


### Visualização e manipulação 🙌

Aqui vão alguns comandos necessários para manipular e visualizar branches e repositórios remotos:

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

**Respectivamente, eles:**

* Mostram a origin linkada
* Renomeia a origin linkada
* Remove a ligação com o seu repositório
* Mostram todas as origin linkadas
* Exibem a branch que você esta manipulando
* Selecionam uma branch de sua escolha
* Volta para a branch main (principal)
* Faz o merge de suas branches diferentes
* Vizualiza todas as branches (tanto remota quanto local)


### Clonando um repositório 👷

##### Se você quiser clonar um repositório já existente e utilizar os arquivos e conteúdos presentes no mesmo, você pode:
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


### Manipulando arquivos ✍️

Em algum determinado momento, você precisará manipular arquivos, ao invés de realizar isso manualmente, você pode fazer isto com os comandos:

#####
    git status
    git add file.txt
    git rm file.txt
    git rm directory 

**Respectivamente, os comandos:**

* Mostram o status dos arquivos presentes em seu diretório
* Adicionam um arquivo
* Removem um arquivo
* Removem um diretório


## Mais comandos úteis 💻

#####
    git config --global user.email YourEmail
    git config --global user.name "Your name"
    git config --global core.excludesfile ~/.gitignore
    git help

**Respectivamente, eles:**

* Configuram o email global do usuário (necessário durante o processo de instalação do Git)
* Configuram o nome global do usuário (necessário durante o processo de instalação do Git)
* Ignora arquivos de sua escolha
* Exibem a ajuda do Git