# **My Brew setup**
This repository show step to install and add Brew to path to make it can be used in any operating system.

### **Image Preview**
- Example Image
![Example Image](./readme-assets/Image%20Preview.png)

### **Go to**
- [Brew homepage](https://brew.sh)

### **Os support**
- Windows (WSL)
- macOS
- Linux

### **Contents**
#### [0. Update apt](./readme.md#0update-apt-for-debian-only-if-you-use-other-you-should-update-your-installer)

#### [1. Install Brew](./readme.md#1-install-brew)

#### [2. Add Brew to PATH](./readme.md#2-add-brew-to-path-for-windows-wsl-and-linux-only)

#### [3. Install useful software for Brew](./readme.md#3-install-useful-software-for-brew)

---

> **Important**
>
> In Windows, you have to [Install WSL](https://github.com/chinhchin/WSL-setup.git) and type every command in WSL to install brew.

## **0. Update apt and install git** (For Debian only, if you use other you should update your installer)
Type these commands in your shell.
```
sudo apt update && sudo apt upgrade
sudo apt-get install git
```

## **1. Install Brew**
Copy and paste this command into your terminal.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

> **Important** (for Windows (WSL) and Linux only)
>
> Don't close terminal or type any command after install brew for [2](./readme.md#2-add-brew-to-path-for-windows-wsl-and-linux-only).

## **2. Add Brew to PATH** (For Windows (WSL) and Linux only)

```
echo 'eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"' >> /home/$USER/.profile
eval "$(/home/linuxbrew/.linuxbrew/bin/brew shellenv)"
```

## **3. Install useful software for Brew**
```
sudo apt-get install build-essential
brew install gcc
```
