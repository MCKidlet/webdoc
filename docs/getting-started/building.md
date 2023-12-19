# Build your first VM
Its time to build your first virtual machine, this part is only for Windows and VMware Workstation, reference the [**Guide**](/guide/intro.md) for more operating systems.

## Download an ISO file!!
You cant do much without an ISO file, aka a Disk Image File, this file contains the operating system and will allow you to set it up, you can use a website like [**BobPony**](https://www.bobpony.com/downloads/) to download an iso. For this tutorial I'll be using a windows 10 (22H2) ISO.

!!If you have an Installer Disk (physical disk) then you can skip this part.

## Create the VM in VMware Workstation

Firstly, you'll want to open **VMware Workstation**
Click **New Virtual Machine**, and then select the type of virtual machine you'd like to make and select **Next**.

But before you click Next, you might want to reference our [**Guide**](/guide/intro.md) to see what option would work best for your VM.

* **Custom** : This option allows you to select what hardware compatibility option you'd like for your virtual machine, reference our [**Guide**](/guide/intro.md) for more information.
* **Typical** (Reccomended) : This option allows you to use the hardware compatibility that your VMware Workstation installation comes with.

Select if you have an **Installer Disk** or **ISO** file and select either the first or second option, if you want to skip **Easy Install** then you can select the **No Disk** option.

**Tip**: The **Easy Install** option allows you to automate some processes like the Windows 10 guest setup stage.

## Easy Install

Click **Next** and enter your Windows 10 product key in the first box, then enter your PC Name in the second box and enter your password and password hint in the other boxes, then click **Next**.

## Regular Install

Click **Next** and select the operating system you'd prefer to install (For this tutorial I'll select Windows 10 x64) and then click **Next**.

## Continued

Enter your VM's Name (The name you'll see in VMware and while searching for it on your hosts filesystem.) then select the location your VM will be saved, then click **Next**.

Select the amount of storage you'd like to allocate to the VM, I reccomend at least 80GB even if it doesn't automatically set the storage amount to that, then click **Next**

Verify the configuration of your virtual machine and click **Next** if everything looks good, click **Customize Hardware** if you would like to make changes to your VM.

Now you're ready to use your VM!
