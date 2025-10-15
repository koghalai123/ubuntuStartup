#ubuntuStartup

#upgrade to new program versions
sudo apt-get update

#install curl
sudo apt install curl

#install brave browser
curl -fsS https://dl.brave.com/install.sh | sh

#install vscode
sudo apt-get install wget gpg

wget -qO- https://packages.microsoft.com/keys/microsoft.asc | gpg --dearmor > packages.microsoft.gpg

sudo install -D -o root -g root -m 644 packages.microsoft.gpg /etc/apt/keyrings/packages.microsoft.gpg

echo "deb [arch=amd64,arm64,armhf signed-by=/etc/apt/keyrings/packages.microsoft.gpg] https://packages.microsoft.com/repos/code stable main" |sudo tee /etc/apt/sources.list.d/vscode.list > /dev/null

rm -f packages.microsoft.gpg

sudo apt install apt-transport-https

sudo apt update

sudo apt install code # or code-insiders

#install htop
sudo apt install htop

#install fuse
sudo apt install fuse

#install git
sudo apt install git

sudo apt install git-lfs

