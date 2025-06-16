#Setting Up Node.js on an Amazon EC2 Instance

### 1. Connect to your Linux instance as ec2-user using SSH.
--- 
### 2. Install node version manager (nvm) by typing the following at the command line.
```sh
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
---
### 3. Load nvm by typing the following at the command line.
```sh
source ~/.bashrc
```
---
### 4. Use nvm to install the latest LTS version of Node.js by typing the following at the command line.
```sh
nvm install --lts
```
> Installing Node.js also installs the Node Package Manager (npm), so you can install additional modules as needed.
---

### 5. Test that Node.js is installed and running correctly by typing the following at the command line.
```sh
node -e "console.log('Running Node.js ' + process.version)"
```
--- 
