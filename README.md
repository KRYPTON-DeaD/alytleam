# alytleam
gentoo-installer
Usage

First, boot into a live environment of your choice. I recommend using an Arch Linux live ISO, as the installer will then be able to automatically download required programs or setup ZFS support on the fly. Afterwards, proceed with the following steps:

pacman -Sy git

(Archlinux) Install git in live environment, then clone:   

git clone https://github.com/KRYPTON-DeaD/alytleam.git

cd gentoo-install

./configure     # configure to your liking, save as gentoo.conf

./install       # begin installation

