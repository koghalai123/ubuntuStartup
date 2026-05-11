# ubuntuStartup
upgrade to new program versions and install Brave browser
```
sudo apt-get update
sudo apt install curl -y
curl -fsS https://dl.brave.com/install.sh | sh
```
install vscode
```
sudo apt-get install wget gpg
wget 'https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64' -O vscode.deb
sudo apt install ./vscode.deb -y
rm vscode.deb
```
Install Zotero
```
wget -qO- https://raw.githubusercontent.com/retorquere/zotero-deb/master/install.sh | sudo bash
sudo apt update
sudo apt install zotero -y
```
install htop, git, and fuse
```
sudo apt install htop -y
sudo apt install fuse -y
sudo apt install git -y
sudo apt install git-lfs
```
Install LaTeX
```
sudo apt install texlive-full
```

Install Python
```
sudo apt install -y python3 python3-pip python3-venv -y
```

# IF YOU GET LOCKED OUT ON LAPTOP BECAUSE OF GRAPHICS ISSUES
Boot into recovery mode and enter the root script
```
init 3
```
On linux Mint
```
sudo apt-get install mint-meta-cinnamon
sudo reboot
```

# If the settings app disappears
```
sudo apt-get remove unity-control-center
sudo apt-get install unity-control-center
```
