# Chapter 1. Setting up the Git
## 1.1 Install Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git could be downloaded in different operatinng systems.

* **_MacOS_**
  - Method 1: using Homebrew
    + Step 1: Download the Homebrew from its [Git Official Website](https://www.git-scm.com/downloads).
      > executing the command **`brew --version`** on terminal to verify whether the homebrew is succefully installed. Once the installation succeeds, the terminal will output the current version number.

      <p align="center">
      <img src='./Images/homebrew.png' width='50%'/>
      </p>
      
    + Step 2: Open the terminal and then type the command **`brew install git`** to install git
      
  - Method 2: using Binary Installar
    + Step 1: Download the binary file on the [Git Official Website](https://www.git-scm.com/downloads).
      > click the binary file and follow the instructions
    + Step 2: Open the terminal and upgrade the git by typing the command **`git clone https://github.com/git/git`**

* **_Windows_**
  - the most used method: using Standalone Installer
    + Step 1: Choose the [correct version](https://www.git-scm.com/download/win), normally it's the 64-bit version.

    <p align="center">
    <img src='./Images/Windows_64bit.png' width='50%' align='center'/>
    </p>

    + Step 2: Click on the downloaded file to start the installation. Proceed with the default settings until the installation is complete.
    + Step 3: Right-click your mouse in empty area, and you'll see a new _"Git Bash"_ option in the menu.

* **_Linux_**
  - Take Ubuntu as an example, more details about installation on other unix systems can be found on [Git Official Website](https://www.git-scm.com/downloads).
    + Step 1: Open the command line window  and execute **`apt-get install git`**

      <p align='center'>
      <img src='./Images/ubuntu.png' width='50%'>
      </p>

> [!NOTE]
> 1. After installation, one can verify using **`git --version`** on the terminal or cmd. With displaying the version number of git, the installation is well done.
    <p align='center'>
    <img src='./Images/gitversion.png' width='50%'>
    </p>
> 2. Actually, I haven't personally tested it on Windows and Linux, but most online tutorials suggest a similar approach, so it should be fine.

## 1.2 Create a Github Account
- Step 1: Use email to register on the [Github Official Website](https://github.com/)
- Step 2: click on the profile icon at the upper right corner of the webpage you'll see the menu
- Step 3: click on the _"Your Profile"_ to view the information. The interface is similar when viewing someone else's profile page.

  <p align='center'>
  <img src='./Images/github_account.png', width='70%'>
  </p>

## 1.3 Configure Git
- **_Basic Setup_**
  
  configure the name and email to create connection between the local machine and the Github by type the following code on terminal or cmd
  ```
  git config --global user.name "Your Github account's name"
  git config --global user.email "Your Github account's email"
  git config --list 
  ```
- **_Create Personal Access Token(PAT)_**

  It could be considered as password and sometimes is required when transporting changes between the local machines and the Github

  <p align='center'>
  <img src='./Images/configure_git.png' height='1%'>
  </p>
