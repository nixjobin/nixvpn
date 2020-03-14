# Welcome to NixVPN #

## How to install ##

## Supported OS ##

- CentOS 7

### Download the package ###

> yum install wget -y && wget https://sourceforge.net/projects/nixvpn/files/latest/download?source=files -O nixvpn-latest.tgz

## Installation ##

> tar -xf nixvpn-latest.tgz && cd nixvpn && ./install.sh install

## How to Uninstall ##

> ./install.sh uninstall

## Admin Panel ##

-------------------------------------------
    Admin URL       : https://IP_ADDRESS:7443/admin
    Admin user      : nixvpnadmin
    Admin Password  : password-created-while-installation

## Change the admin password ##

-------------------------------------------
Login to the server via SSH and run the below command.
> nixvpn-admin-chpass

## Create new VPN User ##

-------------------------------------------
Login to the server via SSH and run the below command.

> nixvpn-user-add

## User Portal ##

-------------------------------------------
    User Portal URL : https://IP_ADDRESS:7443/user
-------------------------------------------

## VPN Client Configuration ##

Ubuntu / Linux : https://www.nixvpn.com/linux-client-configuration/

macOS : https://www.nixvpn.com/macos-client-configuration/

Windows : https://www.nixvpn.com/windows-client-setup-configuration/

For more information, check README file. Please Report any Bug to bug@nixvpn.com

©nixjobin

