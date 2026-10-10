# TobiXu APT Repository

Repositorio apt firmado para rolling release de TobiXu.

**URL:** https://mlmateos.github.io/tobixu-apt-repo

**Uso:** 
echo "deb [signed-by=/etc/apt/keyrings/tobixu-apt-key.gpg] https://mlmateos.github.io/tobixu-apt-repo stable main" | sudo tee /etc/apt/sources.list.d/tobixu.list
sudo apt update
sudo apt install tobixu-gnome-look
