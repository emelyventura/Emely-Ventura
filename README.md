Comandos usados practica 1
============================================

sudo dnf update -y
sudo dnf upgrade -y
cat /etc/yum.repos.d/*.repo
dnf search bashtop
sudo dnf install bashtop -y
bashtop
sudo dnf remove bashtop -y
sudo dnf autoremove -y


Comandos usados practica 2
============================================

crontab -e
0 23 * * * sudo dnf update -y
0 3 * * 0 sudo reboot

at now + 1 minute
rm -rf /tmp/*
Ctrl + D

ls /tmp
ls /tmp


Comandos usados practica 3
============================================

lsblk
sudo fdisk /dev/sdb
n
p
1
Enter
Enter
w

sudo mkfs.ext4 /dev/sdb1
mkdir ~/Disco20GB
sudo mount /dev/sdb1 ~/Disco20GB
cd ~/Disco20GB
touch AdrianAlcantara.txt
ls

sudo umount ~/Disco20GB
sudo mount /dev/sdb1 /mnt
cd /mnt
ls
