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

### docker & docker-compose installation
 - [docker](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-on-debian-10)
 - [docker-compose](https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-debian-10)
 - [change docker_images dir](https://linuxconfig.org/how-to-move-docker-s-default-var-lib-docker-to-another-directory-on-ubuntu-debian-linux)
