# **My Brew setup**
This repository show step to install and add Brew to path to make it can be used in any operating system.

### **Image Preview**
- Example Image
![Example Image](https://github.com/chinhchin/Brew-setup/blob/0.0.b.0/readme-assets/Image%20Preview.png?raw=true)

### **Go to**
- [Brew homepage](https://brew.sh)

### **Os support**
- Windows (WSL)
- macOS
- Linux

### **Contents**
#### [1. Update apt](./readme.md#0update-apt-for-debian-only-if-you-use-other-you-should-update-your-installer)

#### [1. Install Brew](./readme.md#1-install-brew)

#### [2. Add Brew to PATH](./readme.md#2-add-brew-to-path-for-windows-wsl-and-linux-only)

#### [3. Install useful software for Brew](./readme.md#3-install-useful-software-for-brew)

---

> **Important**
>
> In Windows, you have to [Install WSL](https://github.com/chinhchin/WSL-setup.git) and type every command in WSL to install brew.

## **0. Update apt** (For Debian only, if you use other you should update your installer)
Type these commands in your shell.
```
sudo apt update && sudo apt upgrade
```

## **1. Install Brew**
Copy and paste this command into your terminal.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

> **Important** (for Windows (WSL) and Linux only)
>
> Don't close terminal or type any command after install brew for [2](https://github.com/chinhchin/Brew-setup/blob/0.0.b.0/readme.md#2-add-brew-to-path-for-windows-wsl-and-linux-only).

## **2. Add Brew to PATH** (For Windows (WSL) and Linux only)
After installing brew you can see in topic "*Next steps*" in "*Run these two commands in your terminal to add Homebrew to your PATH*"
Run those two command to add Homebrew to your PATH.

- **Example in WSL**
![WSL example](https://github.com/chinhchin/Brew-setup/blob/0.0.b.0/readme-assets/Add%20Brew%20to%20PATH/WSL%20example.png?raw=true)

- **Example in Linux**
![Linux example](https://github.com/chinhchin/Brew-setup/blob/0.0.b.0/readme-assets/Add%20Brew%20to%20PATH/Linux%20example.png?raw=true)

## **3. Install useful software for Brew**
```
sudo apt-get install build-essential
brew install gcc
```
