# SETTING UP MY HOMELAB 

# ⏸️ DOCUMENTATION IS CURRENTLY PAUSED ⏸️

I will be building a new PC with much better specs!
This means I will need to rebuild my homelab on my new system when it is built, and that setup documentation will replace this current one.


### VM Installation

First I navigated to https://www.virtualbox.org/wiki/Downloads to download and install VirtualBox and the VirtualBox Extension Pack.

![image](https://github.com/user-attachments/assets/a1d2adbb-4530-42d1-8b64-fe1afab157f0)



### Download Relevant ISO files

ISO files to a VM are CD/DVD disks to a physical drive. 

I will be using Kali Linux and Ubuntu.

https://www.kali.org/get-kali/#kali-installer-images 

![image](https://github.com/user-attachments/assets/b2c71b5e-6e1a-4fc9-92eb-9b18a2c0fa0d)

https://ubuntu.com/download/desktop 

![image](https://github.com/user-attachments/assets/1984e730-be3f-462f-87ff-cdbb881feb9e)

### Load and Configure ISO Files into VirtualBox

In VM VirtualBox Manager, hit CTRL + N to create a new Virtual Machine.

I then entered the appropriate named and selected its respective ISO Image. Then Next.

![image](https://github.com/user-attachments/assets/b04f7864-50ac-4b8f-a390-43cbc6732fdf)

I increased the base memory to 4 GB, as I plan to have 2 running simultaneously.

![image](https://github.com/user-attachments/assets/94eeda99-ead7-47c8-9209-f69b60ad744c)

No changes were made to the rest, finally finishing the setup for Kali. 

Repeat the process for Ubuntu.

Power on both Kali and Ubuntu and complete initial install. After installing, you will be prompted to restart.

*Please note: I do not recommend installing both at the same time like I did, it took a very, very long time for both to complete.

![image](https://github.com/user-attachments/assets/73700e3a-948f-4c4f-8cdc-d33ce8977289)

### Setup the Network


CTRL + H, will open the Network Manager. Click on NatNetworks, Right-Click and select create.

Then change the systems to use the network that was created.

![image](https://github.com/user-attachments/assets/3489d707-dec2-489b-a9e3-80861062614e)


### Update the Operating Systems to Latest Verison
Kali: run command 1)
Ubuntu: run both commands

1) sudo apt update && sudo apt upgrade -y
2) sudo apt install -y build-essential git curl wget

You may be prompted to restart the system to complete the installation.

### Install tools



### Create Baseline Snapshots


<!-- notion continue after installtion and reboots 6:30 -->
