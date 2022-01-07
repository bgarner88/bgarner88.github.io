---
layout: post
title: "How to Install an Ubuntu VM with VMware Workstation"
categories: vmware
---

## Introduction

This guide will walk you through downloading and installing VMware Workstation Player with a Linux Ubuntu virtual machine.

## Dowloading the Necessary Files

First, you'll need to download VMware Workstation and the Ubuntu iso file.

### WMware Workstation

Navigate to [https://www.vmware.com/](https://www.vmware.com/). 

On the top menu, click **Workspace** to bring up a dropdown menu. 

Under **Desktop Hypervisor** click **Workstation Player**

![WS Player Download](\assets\img\vmware\wsplayer-download.jpg)

Click **Download for Free**.

![WS Player Download](\assets\img\vmware\wsplayer-download-2.jpg)

Under **Product Downloads** click **Go to Downloads**.

![WS Player Download](\assets\img\vmware\wsplayer-download-3.jpg)

Click **Download Now** beside the Windows 64-bit file.

![WS Player Download](\assets\img\vmware\wsplayer-download-4.jpg)

Save the file anywhere you would like.

### Ubuntu Iso

Next you'll need to download the Ubuntu iso file.

Navigate to [https://ubuntu.com/](https://ubuntu.com/).

On the top menu click **Download** then under **Ubuntu Desktop** choose the **LTS** version.

![Ubuntu Download](\assets\img\vmware\ubuntu-download.jpg)

The download should automatically start. If not, click the **download now** link on the next page. Save the file anywhere you would like. 

## Installing VMware Workstation

Now you can install VMware Workstation. Go to where you saved the install file and run it by double clicking or right-clicking and choosing **Open**.

Make sure the option to use VMware Workstation for free is selected and click **Continue**.

![VMware Install](\assets\img\vmware\wsplayer-install-1.jpg)

Click **Next** through the installer, using the default options, until the installer completes. 

When the installer finishes it will open VMware automatically and you'll be ready to install Ubuntu.

![VMware Install](\assets\img\vmware\wsplayer-install-2.jpg)

## Installing Ubuntu

Click **Create a New Virtual Machine**.

Choose the **installer disc image file** option. 

Click **Browse** and locate the ubuntu iso file you downloaded earlier, then click **Next**.

![WMware Install](\assets\img\vmware\wsplayer-install-3.jpg)

Enter a **Full Name**, **User Name**, and **Password**.

![WMware Install](\assets\img\vmware\wsplayer-install-4.jpg)

Name the Virtual Machine anything you like and click **Browse** to choose an install location. The default will be C:\Users\currentuser\Documents\Virtual Machines where **currentuser** is your user name.

Click **Next**.

![WMware Install](\assets\img\vmware\wsplayer-install-5.jpg)

At the next screen you can specify the disk space used for the VM. Click **Next** to use the default settings.

![WMware Install](\assets\img\vmware\wsplayer-install-6.jpg)

The next screen gives you the option to customize the hardware used if you wish. Click **Finish** to use the default settings. Make sure the checkbox is ticked to power on the virtual machine after creation.

![WMware Install](\assets\img\vmware\wsplayer-install-7.jpg)

And that's it. The install will take several minutes. When it's completed, VMware will open the new virtual machine and you can login with the user name and password you created earlier.

![WMware Install](\assets\img\vmware\wsplayer-install-8.jpg)
