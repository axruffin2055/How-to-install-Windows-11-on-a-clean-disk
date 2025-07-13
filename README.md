Quote for the mind:  
Life is like riding a bicycle. To keep your balance, you must keep moving.  
Albert Einstein  

# How-to-install-Windows-11-on-a-clean-disk.  

Introduction  
Guys and gals, before we get into this, I highly recommend installing a Linux Operating System (OS) on a USB.  
Why install another OS on an USB, when you already have an OS? Because if you embark on this quest:  
"How-to-install-Windows-11-on-a-clean-disk." and things do not go as planned such as technology decides  
that it does not want to configurate software or hardware for whatever reasons, then you may need to  
download software, or fix the problems using another OS with internet. It is better to have an OS backup  
if by change while working on this project, Windows 11 will not boot up. Also, please do not panic because I got you covered:  
https://github.com/axruffin2055/How-to-install-Windows-11-on-a-clean-disk./blob/main/Install%20Ubuntu  
This link will help with installing Ubuntu on a USB. Now on to this project.  

Installing Windows 11 on a clean disk is useful when starting fresh, wiping out preinstalled bloatware,  
dual-booting with Linux, or recovering from severe system issues. A clean install ensures no leftover system  
clutter or malware and gives you complete control over disk partitioning. For instance, the need to gain more  
disk space for the Linux OS on Windows 11 disk was reason enough to wipe the disk and gain better control  
toward the dual-booting quest. 

Description  
This guide walks you through creating a bootable Windows 11 installer, wiping a drive safely,  
installing Windows 11, and troubleshooting hardware driver issues. It’s especially useful for  
developers, IT technicians, or advanced users looking to dual boot or maintain clean system environments.

Features  
- Step-by-step instructions to create a clean Windows 11 install
- Multiple methods to wipe a disk securely
- USB installer tools for both Windows and Linux
- Manual driver installation help
- Tips for dual-booting readiness


Problem it Solves
- Removes preinstalled orignal equipment manufacturer (OEM) systems or malware
  (Non-OEM helps with system upgrade cost and flexibility)
- Prepares a PC for dual boot with Linux
- Recovers a PC after OS corruption

Technologies Used
- Operating Systems: Windows 11, Rocky Linux 9
- Command-line Tools: Bash, Diskpart, parted, wipef
- File Systems: NTFS, FAT32, XFS
- Partitioning Tools: GParted, WoeUSB, Ventoy
- Dependencies: ntfs-3g, pnputil, Rufus
- Utilities: Device Manager, Shift+F10 (Windows Setup CLI), Git (optional for repo cloning)

Prerequisites
- A working PC to prepare the installer
- USB drive (8GB minimum, 16GB or more is recommended)
- Reliable internet to download ISO and tools
- Backed-up personal data from Windows 11 disk
- Familiarity with boot menus/BIOS settings

Installation Steps  
https://github.com/axruffin2055/How-to-install-Windows-11-on-a-clean-disk./blob/main/Step-by-Step
