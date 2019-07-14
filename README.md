# lfspacman
A small script that lets you use the Arch linux packages repo and it's package manager - Pacman, after you've installed and booted LFS.

## how to use:
Run in LFS (with a working network connection):  
```bash
cd /tmp  
git clone https://github.com/uditkarode/lfspacman.git  
cp lfspacman/lfspacman /bin  
chmod +x /bin/lfspacman  
ls -hal /sources > /etc/lfspacman.conf  
lfspacman  
```
