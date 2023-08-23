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
    
* 如您所見，翻譯是即時完成的，可能存在一些錯誤，請忽略此行為。
  
<img src="https://github.com/Anmol-Baranwal/Cool-GIFs-For-GitHub/assets/74038190/9db4b864-a764-468f-9052-7bfa1bfe9a74" width="300">

![](https://i.imgur.com/waxVImv.png)

### 演示👶

GitHub 擁有大量可用命令，每個命令執行不同的功能。 <br/>
該存儲庫不會向您介紹基本的 GitHub 概念，它只會向您展示一些最常用的 GitHub 命令。

此處可見的每個命令都代表一個函數，無論它是負責進行小型提交還是幫助您操作分支。

---

### 如何提交🐤

要進行提交，需要執行幾個步驟。首先，您需要確保您的 GitHub 配置文件中存在現有存儲庫。
當您邁出創建存儲庫的第一步時，同樣的內容已經對您有所幫助，但無論如何，這裡對每個步驟所代表的內容進行了簡短的解釋。

##### 在 Git 中初始化文件。
      git init
      
##### 如果您想添加自述文件。
      git add README.md

##### 使用您選擇的消息進行提交（請記住，將顯示此消息）。
      git commit -m "first commit"

##### 此命令將幫助您穩定上傳更改所需的連接，請注意，此命令會將項目的本地存儲庫與 GitHub 上的存儲庫同步。
      git remote add origin https://github.com/YourUserName/YourRepoName.git

##### 使用此命令，您可以選擇要轉儲內容的分支。
       git branch -M main

##### 執行推送（當說 _push_ 時，它只不過是拉取本地內容、同步它並將其上傳到 Git 存儲庫的行為）。
      git push -u origin main

他看見 ？提交和推送存儲庫並不難，只要嚴格遵循這些步驟，在您的個人資料中創建存儲庫後，您將擁有所有可用內容！
重要的是要記住，這些只是第一步，顯然在整個項目中您將更頻繁地更新它，但是，無需重複整個過程，只需執行以下一些步驟，新的更新就會可用:

#####
      git add . 
      git commit -m "update version"
      git push


### 可視化和操作🙌

以下是操作和查看分支和遠程存儲庫所需的一些命令：

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

**他們分別：**

* 顯示鏈接來源
* 重命名鏈接源
* 刪除存儲庫的鏈接
* 顯示所有鏈接的來源
* 顯示您正在辦理的分行
* 選擇您喜歡的分支
* 返回主分支
* 合併不同的分支
* 顯示所有分支機構（遠程和本地）


### 克隆存儲庫👷

##### 如果您想克隆現有存儲庫並使用它包含的文件和內容，您可以：
    git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY


### 文件操作✍️

有時您需要操作文件，您可以使用以下命令來代替手動操作：

#####
   git status
    git add file.txt
    git rm file.txt
    git rm directory 

**分別是命令：**

* 查看目錄中存在的文件的狀態
* 添加一個文件
* 刪除文件
* 刪除目錄


## 更多有用的命令💻

#####
    git config --global user.email YourEmail
    git config --global user.name "Your name"
    git config --global core.excludesfile ~/.gitignore
    git help

**他們分別：**

* 配置用戶的全局電子郵件（Git安裝過程中需要）
* 設置全局用戶名（Git安裝過程中需要）
* 忽略您選擇的文件
* 顯示 Git 幫助
