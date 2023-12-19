# The VM Guide

This guide will teach you how VM's work and their uses, this guide also goes in depth on programs such as VMware Workstation Pro and Player, Hyper-V, Oracle VirtualBox, UTM, QEMU, and Parallels.


## The rundown

* [**VMware Workstation**](https://www.vmware.com/products/workstation-pro.html) ([**In-Depth Look**]()): This software works on **Windows** and **Linux** and is one of the most mainstream virtualization solutions out there, this software can create **MacOS**, **Windows**, and **Linux** guests (VM's), this is one of the most versatile, user friendly virtualization solutions and is my biggest reccomendation.
* [**Hyper-V**](https://learn.microsoft.com/en-us/virtualization/hyper-v-on-windows/about/) ([**In-Depth Look**]()): This software only works on **Windows** but you must have access to virtualization on your PC if you want to use Hyper-V, this will not work on the Home edition of Windows. This solution is just about as advanced as **VMware Workstation** but it can only run modern guest operating systems such as Windows 10 and later.
* [**Oracle VirtualBox**](https://www.virtualbox.org/) ([**In-Depth Look**]()): This is a simple and user friendly software for beginners that are getting into the VM space, this software works on **Windows**, **MacOS** (Intel), and **Linux**, however this software is more limited and security updates often are late to come which can make VirtualBox a bad idea if you're planning to use it to test out malware.
* [**UTM**](https://mac.getutm.app/) ([**In-Depth Look**]()): This is a good alternative to **VirtualBox** and only runs on **MacOS** (11 and later) and **iOS**, this is a QEMU based virtualization solution that allows you to run virtual machines just like how you would on another solution, however you may be limited by Apple Silicon or an ARM SoC, **UTM** has the ability to emulate x86 and x64 processors but it is slow and unreliable.
* [**QEMU**](https://www.qemu.org/) ([**In-Depth Look**]()): This is a pretty advanced virtualization solution that works on **Linux**, **MacOS** (UTM), and **Windows**. It is the most versatile and lets you run even an iPod on it, if you're using the bare bones version of **QEMU** then you'll have to get used to the command line interface rather than a user friendly UI, although there are some UI alternatives, they may be more limited then using the command line.
* [**Parallels**](https://www.parallels.com/) ([**In-Depth Look**]()): This is the most simple and straightforward virtualizaation solution on this list, I am not planning on going in depth on this but I will mention it anyways, this solution only works on **MacOS** and allows you to run **Windows**, **Linux**, and **MacOS** on it, the features of **Parallels** are fairly limited but it is great if you're new and want to experiment a little.

!> The **In-Depth Look** options won't be available until this intro page is completely finished.

## Learning Virtualization Software

We'll be learning VirtualBox since it's compatible with most OS' and is very simple to use for a first time user.

When you launch into **VirtualBox** after downloading it, you will see a screen similar to the one shown below.
![Launch Screen](/images/IMG_0386.png)
**Let's go through the options on this screen.** There's some comoon options you'll see across virtualization software, such as **importing a virutal machine**, **adding a virtual machine**, and **modifying a virtual machine**. These options are essential to modern virtualization software. Now you've started building your first virtual machine, the options may seem overwhelming when you're on your own, but don't fret, it's really simple.
![Building Screen](/images/IMG_0387.jpeg)
**Let's learn what all the options do.** Now this may not exactly replicate what software you're using, but it still has the same elements, a VM directory, a VM name, and an OS the VM will use. These are also very commonly seen throughout other GUI virtualization software such as VMware Workstation, UTM, and so on.

* **VM Directory** : The location of where your virtual machine is stored, the default one may not be a location where you have enough storage, you might want to relocate your virtual machine to your D: drive instead.
* **VM Name** : This is the name you'll give your virtual machine, you can stick with the preset name it gives you but if you want to immediately recognize your VM from the other ones you may have on your system, it's best to name it.
* **VM OS** : This is the operating system you'll put on your virtual machine, many virtualization softwares require you to specify the operating system so your virtual machine can run properly.

