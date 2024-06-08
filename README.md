# Chapter 1. Setting up the Git
## 1.1 installing Git
Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. Git could be downloaded in different operatinng systems.

* **_MacOS_**
  - Method 1: using Homebrew
    + Step 1: Download the Homebrew from its [Official Website](https://www.git-scm.com/downloads).
      > executing the command **`brew --version`** on terminal to verify whether the homebrew is succefully installed. Once the installation succeeds, the terminal will output the current version number.

      <p align="center">
      <img src='./Images/homebrew.png' width='50%'/>
      </p>
      
    + Step 2: Open the terminal and then type the command **`brew install git`** to install git
      
  - Method 2: using Binary Installar
    + Step 1: Download the binary file on the [Official Website](https://www.git-scm.com/downloads).
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
  - Take Ubuntu as an example, more details about installation on other unix systems can be found on [Official Website](https://www.git-scm.com/downloads).
    + Step 1: Open the command line window  and execute **`apt-get install git`**

      <p align='center'>
      <img src='./Images/ubuntu.png' width='50%'>
      </p>

> [!NOTE]
> 1. After installation, one can verify using **`git --version`** on the terminal or cmd. With displaying the version number of git, the installation is well done.
