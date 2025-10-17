# ubuntuStartup

# upgrade to new program versions and install Brave browser
```
sudo apt-get update

sudo apt install curl

curl -fsS https://dl.brave.com/install.sh | sh
```
# install vscode
```
sudo apt-get install wget gpg

wget 'https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64' -O vscode.deb

sudo apt install ./vscode.deb

rm vscode.deb
```
# Install Zotero
```
wget -qO- https://raw.githubusercontent.com/retorquere/zotero-deb/master/install.sh | sudo bash
sudo apt update
sudo apt install zotero
```
# install htop, git, and fuse
```
sudo apt install htop

sudo apt install fuse

sudo apt install git

sudo apt install git-lfs
```
