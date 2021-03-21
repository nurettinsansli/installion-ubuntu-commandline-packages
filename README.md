<p class="has-line-data" data-line-start="0" data-line-end="14">#Jenkins<br>
sudo apt update<br>
sudo apt search jdk<br>
sudo apt install openjdk-8-jre<br>
sudo apt install openjdk-8-jre-headless<br>
wget -q -O - <a href="https://pkg.jenkins.io/debian/jenkins.io.key">https://pkg.jenkins.io/debian/jenkins.io.key</a> | sudo apt-key add -<br>
sudo nano /etc/apt/sources.list<br>
deb <a href="https://pkg.jenkins.io/debian">https://pkg.jenkins.io/debian</a> binary/<br>
sudo apt update<br>
sudo apt install jenkins<br>
sudo systemctl start jenkins<br>
sudo systemctl enable jenkins<br>
ip a<br>
localhost:8080</p>
<p class="has-line-data" data-line-start="15" data-line-end="19">#git<br>
sudo apt update<br>
sudo apt install git<br>
git --version</p>
<p class="has-line-data" data-line-start="20" data-line-end="24">#vscode<br>
<a href="https://code.visualstudio.com/Download">https://code.visualstudio.com/Download</a><br>
cd ~/Downloads<br>
sudo dpkg -i code_1.26.0-1534177765_amd64.deb</p>
<p class="has-line-data" data-line-start="25" data-line-end="27">#vlc<br>
sudo snap install vlc</p>
<p class="has-line-data" data-line-start="28" data-line-end="35">#GlobalProtect<br>
download-&gt; <a href="https://drive.google.com/file/d/17HWBEUczwoHandU2L7v9jmDiJHukeSkD/view">https://drive.google.com/file/d/17HWBEUczwoHandU2L7v9jmDiJHukeSkD/view</a><br>
tar -xvf ~/pkgs/PanGPLinux-5.1.0.tgz<br>
sudo dpkg -i GlobalProtect_deb-5.1.0.0-19.deb<br>
how to connect vpn?<br>
globalprotect connect --portal <a href="http://sslvpn.hepsiburada.com">sslvpn.hepsiburada.com</a><br>
globalprotect disconnect</p>
<p class="has-line-data" data-line-start="36" data-line-end="41">#studio3t<br>
navigate to download page<br>
cd ~/Downloads<br>
tar -xzf studio-3t-linux-x64.tar.gz<br>
sh <a href="http://studio-3t-linux-x64-no-shell.sh">studio-3t-linux-x64-no-shell.sh</a></p>
<p class="has-line-data" data-line-start="42" data-line-end="44">#slack<br>
<a href="https://slack.com/intl/en-tr/help/articles/212924728-Download-Slack-for-Linux--beta-">https://slack.com/intl/en-tr/help/articles/212924728-Download-Slack-for-Linux–beta-</a></p>
<p class="has-line-data" data-line-start="45" data-line-end="47">#elasticsearch-head chrome extension<br>
<a href="https://chrome.google.com/webstore/detail/elasticsearch-head/ffmkiejjmecolpfloofpjologoblkegm">https://chrome.google.com/webstore/detail/elasticsearch-head/ffmkiejjmecolpfloofpjologoblkegm</a></p>
<p class="has-line-data" data-line-start="48" data-line-end="54">#idealC<br>
$ sudo snap install intellij-idea-community --classic<br>
OR<br>
$ sudo snap install intellij-idea-ultimate --classic<br>
OR<br>
$ sudo snap install intellij-idea-educational --classic</p>
<p class="has-line-data" data-line-start="55" data-line-end="60">$ intellij-idea-community<br>
OR<br>
$ intellij-idea-ultimate<br>
OR<br>
$ intellij-idea-educational</p>
<p class="has-line-data" data-line-start="61" data-line-end="63">#spotify<br>
snap install spotify</p>
<p class="has-line-data" data-line-start="64" data-line-end="66">#postman<br>
sudo snap install postman</p>
<p class="has-line-data" data-line-start="67" data-line-end="69">#pyhton<br>
sudo apt install python</p>
<p class="has-line-data" data-line-start="70" data-line-end="74">#lightshot<br>
sudo apt-get install wine<br>
wget <a href="http://app.prntscr.com/build/setup-lightshot.exe">http://app.prntscr.com/build/setup-lightshot.exe</a><br>
wine ./setup-lightshot.exe</p>
<p class="has-line-data" data-line-start="75" data-line-end="77">#simplescreenrecorder<br>
sudo apt install simplescreenrecorder</p>
<p class="has-line-data" data-line-start="78" data-line-end="80">#flameshot<br>
sudo apt install flameshot</p>
<p class="has-line-data" data-line-start="81" data-line-end="83">#libreoffice<br>
sudo apt install libreoffice</p>
<p class="has-line-data" data-line-start="84" data-line-end="90">#whenistartautomation<br>
#Amazon corretto —&gt; When i open automatically-&gt; OpenJDK’nın üretime hazır bir dağıtımıdır ve sınırsız Java uygulamaları oluşturmak ve düzenlemek için ihtiyacınız olan her şeyi sunar.<br>
#Gherkin plugin —&gt; For *.feature files<br>
#Cucumber for Java —&gt; plugin<br>
#undefined glue hatası—&gt; package adı olacak<br>
#baseUrl not found—&gt; set vm options -Dgrid=false -DbaseUrl=http://www.google.com</p>
<p class="has-line-data" data-line-start="91" data-line-end="97">#java<br>
sudo apt install openjdk-8-jdk<br>
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64<br>
echo $JAVA_HOME<br>
export PATH=$PATH:$JAVA_HOME/bin<br>
echo $PATH</p>
<p class="has-line-data" data-line-start="98" data-line-end="112">#nodejs<br>
sudo apt install nodejs<br>
node -v<br>
#npnm<br>
sudo apt install npm<br>
npm -v<br>
#npm amqlib<br>
npm install amqplib<br>
#curl<br>
sudo apt update<br>
sudo apt upgrade<br>
sudo apt install curl<br>
#second<br>
gsettings set org.gnome.desktop.interface clock-show-seconds true</p>
<p class="has-line-data" data-line-start="113" data-line-end="128">#media codec?<br>
sudo apt update<br>
sudo apt install ubuntu-restricted-extras<br>
&amp;<br>
sudo apt-get update &amp;&amp; sudo apt-get upgrade<br>
&amp;<br>
sudo apt install ffmpeg<br>
&amp;<br>
sudo snap install opera<br>
&amp;<br>
sudo apt-get -y update &amp;&amp; apt-get -y install chromium &amp;&amp; mv /usr/lib/x86_64-linux-gnu/opera/libffmpeg.so /usr/lib/x86_64-linux-gnu/opera/libffmpeg.so.old &amp;&amp; cp /usr/lib/chromium/libffmpeg.so /usr/lib/x86_64-linux-gnu/opera/<br>
&amp;<br>
Software update&amp;upgrade-&gt; additional drivers &gt; select gpu driver&gt; click to apply changes<br>
&amp;<br>
sudo apt install chromium-codecs-ffmpeg-extra</p>
<p class="has-line-data" data-line-start="129" data-line-end="131">#howtocleardnscache<br>
sudo systemd-resolve --flush-caches</p>
<p class="has-line-data" data-line-start="132" data-line-end="134">#howtoclearchromednscache<br>
chrome://net-internals/#dns</p>
