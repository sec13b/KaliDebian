# KaliDebian
Transform Debian in Kali :D<br><br><br>
<br><br><br>
sudo curl https://archive.kali.org/archive-key.asc -o /etc/apt/trusted.gpg.d/kali-archive-key.asc<br><br>
sudo sh -c "echo 'deb http://http.kali.org/kali kali-rolling main non-free contrib' >> /etc/apt/sources.list"<br>
sudo apt-get update<br>
sudo apt-get upgrade<br>
sudo apt-get dist-upgrade<br>
sudo reboot<br>
sudo apt-get autoremove --purge<br>
sudo apt-get install kali-linux-headless<br>
sudo apt clean<br>
