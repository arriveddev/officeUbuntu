# How to install Microsoft Office on Ubuntu 20.04/22.04/24.04 LINUX

## Step 1. Enable 32-bit support
sudo dpkg --add-architecture i386;

## Step 2. Install winbind and winetricks
sudo apt update && sudo apt upgrade;
sudo apt-get install winbind;
sudo apt-get install -y winetricks;

## Step 3. Install PlayOnLinux
sudo apt install playonlinux

## Step 4. Install Office 2016 on Ubuntu
Prepare the Office 2016 installer: If you don't have it already, click here to download Microsoft Office 2016 Full 32/64-bit. (https://arriveddev.com/office-2016-professional-plus-full-activate/)
Open the menu and search for "PlayOnLinux". Click on it to launch the application.

Click Office -> Install, select Microsoft Office 2016 Method B.
Click on "Next" and select "Use a setup file in my computer.
Find office2016.exe and click continue.

Done!
Search Excel, Word on the Menu and Open =>>

Source: https://arriveddev.com/install-microsoft-office-on-ubuntu/

