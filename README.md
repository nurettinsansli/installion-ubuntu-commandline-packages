#Jenkins
sudo apt update
sudo apt search jdk
sudo apt install openjdk-8-jre
sudo apt install openjdk-8-jre-headless
wget -q -O - https://pkg.jenkins.io/debian/jenkins.io.key | sudo apt-key add -
sudo nano /etc/apt/sources.list
deb https://pkg.jenkins.io/debian binary/
sudo apt update
sudo apt install jenkins
sudo systemctl start jenkins
sudo systemctl enable jenkins
ip a
localhost:8080

#git
sudo apt update
sudo apt install git
git --version

#vscode
https://code.visualstudio.com/Download
cd ~/Downloads
sudo dpkg -i code_1.26.0-1534177765_amd64.deb

#vlc
sudo snap install vlc

#anyconnect


#studio3t
cd ~/Downloads
wget https://download.studio3t.com/robomongo/linux/robo3t-1.4.0-linux-x86_64-12e54cc.tar.gz
tar -xzf studio-3t-linux-x64.tar.gz
sh studio-3t-linux-x64-no-shell.sh


