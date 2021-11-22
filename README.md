# **How to install OlaiOS**
<img src="https://i.imgur.com/X8QbiuX.png"/>

# **Features**
- Preinstalled Steam
- Brave Browser as default browser
- Custom Neofetch Logo
- Custom wallpapers
# **Making a Bootable Device**
#### Download regular arch Linux
#### https://archlinux.org/download
#### Make a bootable USB Drive
#### For Linux and Mac Users, Download BalenaEtcher https://www.balena.io/etcher/
#### For Windows Users, Download BalenaEtcher or Rufus https://rufus.ie/en/

After you made a bootable USB Drive launch it from BIOS / UEFI
<br />After Arch Linux launches type

## **Building the OS**
    sudo pacman -Syyu
#### That will update your operating system, but this may fail because of low storage, and after the update type

    sudo pacman -S git
 
#### That will install git which will allow you to download OlaiOS
<br />After Git it downloaded type
    
    git clone https://github.com/OlaYZen/OlaiOS.git

#### After you have git clone, go to the OlaiOS Folder by Typing

    cd OlaiOS/

## **Selecting Desktop Environments**
#### Right now, There are 6 Desktop environments ready to download, there is

- Cinnamon
- GNOME
- KDE
- MATE
- Xfce4
- Budgie

#### Choose your Desktop environment by running example

    cd KDE
#### After choosing your Desktop environment select your Drivers which matches your GPU by running
    
    cd Nvidia
#### or 

    cd AMD

## **Start the Script**
#### After entering the Driver folder, run
    
    chmod +x installer.sh
    
#### then

    ./installer.sh

#### All necessary files will be automatically downloaded for you,
After installation you will be asked to create an account. 
Create the account and restart the computer

#### OlaiOS should be fully installed

## **Official Wiki**
- [Wiki](https://github.com/OlaYZen/OlaiOS/wiki)
- [Discord](https://discord.gg/s7VPXh3qtS)
- [Default Options](https://github.com/OlaYZen/OlaiOS/wiki/Default-Options)
- [Frequently asked Question](https://github.com/OlaYZen/OlaiOS/wiki/Frequently-asked-Question)
