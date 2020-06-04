# Debian Installation gotchas

Download procedure

debian.org > Getting Debian > Try Debian live > DVD/USB amd64 >  /images/unofficial/non-free > live+nonfree > amd64 > isohybrid > kde+nonfree.iso

## WHILE INSTALLATION

### ROOT PASSWORD

Dont enter root password. Move on.

### GRUB

- Install grub `YES`
- Select the hard drive where to install grub


## AFTER INSTALLATION

### WIFI
follow this wiki guide
    
    https://wiki.debian.org/wl

### DISABLE GRUB SCREEN

-  `sudo vi /etc/default/grub`
- set GRUB_TIMEOUT=0
- `sudo update-grub`
