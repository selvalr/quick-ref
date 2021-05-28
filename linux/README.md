# Linux Quick Ref

### What is Linux and Distro

- Linux is Operating System like windows and Macos
- Linux is free and opensource 
- Linux means kernal
- Distribution means different flavours of linux kernal
- ubuntu, centos, redhat, kali linux, fedora, linux mint, parot os, etc.......
- LTS - long time support
- debian - apt install $SOFTWARE-NAME - ubuntu, parrot, kali
- redhat - yum install $SOFTWARE-NAME - centos, redhat, fedora

### Filesystem

- In linux everything is file
- check linux filesystem n youtube


### Basic Commands
``` bash
cd # Change dir # without option take u to home dir
cd $dir_name # change dir
cd .. # go to previous dir
pwd # present working dir
ls # list
ls -la # more info
mkdir $dir_name # create dir
rmdir $dir_name # delete empty dir
touch akilan.txt # create a empty file
cat akilan.txt # View file content in command line
vi akilan.txt # update file press i to insert data, press escape to come out insert mode
# press : and type wq to write and quit the editor
rm akilan.txt # remove file
rm -rf $dir_name# delete a dir and sub dir
cp akilan.txt akilan-copy.txt # file copy
mv akilan.txt akilan-mv.txt # file move
cp -rf html/ html-new/ # copy folder, subfolders, files
mv html/ html-new/ # mv folder, subfolders, files
history # list of previous commands

```

### Install software in Debian based [ ubuntu, kali linux etc..]
```bash
sudo apt update # check if upgrade needed, check all the URLs 
sudo apt list --upgradable # list all the available update
sudo apt upgrade -y # install the upgrade
sudo apt autoclean # clean unwanted packages
sudo apt autoremove # clean unwanted insatlled packages
sudo apt install git # install individual tools here git
```