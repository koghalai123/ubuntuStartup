#ubuntuStartup

#upgrade to new program versions

sudo apt-get update

#install curl

sudo apt install curl

#install brave browser

curl -fsS https://dl.brave.com/install.sh | sh

#install vscode

sudo apt-get install wget gpg

wget 'https://code.visualstudio.com/sha/download?build=stable&os=linux-deb-x64' -O vscode.deb

sudo apt install ./vscode.deb

rm vscode.deb

#install htop

sudo apt install htop

#install fuse

sudo apt install fuse

#install git

sudo apt install git

sudo apt install git-lfs

