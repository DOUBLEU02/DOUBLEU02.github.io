# How to install Ubuntu 22.04 on Vmware Workstation in Widows 10 for Macbook Pro 2013

### Step 1 : Install Windows 10 on your Mac using Boot Camp Assistant

Install Windows 10 on your Mac using Boot Camp Assistant.[Click here](https://support.apple.com/en-us/HT201468)

### Step 2 : Download Vmware Workstation on Windows 10

Download Vmware Workstation Pro from their official website and install it on your Windows 10. 

![image](https://user-images.githubusercontent.com/85865681/182914432-b4e9dda8-d66f-49bb-bcad-32073959ebd9.png)

### Step 3 : Download Ubuntu OS ISO file

Download Ubuntu 22.04 OS ISO file from its official website.

![image](https://user-images.githubusercontent.com/85865681/182914576-b0d2a3a9-65e5-4ca3-96b7-384acad18b3d.png)

### Step 4 : Open Vmware Workstation

Open Vmware Workstation and Click on Create a new Virtual Machine.

![image](https://user-images.githubusercontent.com/85865681/182914658-3bcc27c8-990a-40fe-a0cd-1ba13cf9f1af.png)

### Step 5 : Setup OS settings on Vmware Workstation

choose Installer disc image file (iso): to make the workstation to detect that the iso file is appropriate or not.

![image](https://user-images.githubusercontent.com/85865681/182914692-2fc11bf6-f2af-4dcc-bd10-e062cb5d4bc7.png)

Here is the information about your OS such a full name, user name and password.

![image](https://user-images.githubusercontent.com/85865681/182914868-84534390-d590-4a72-aa68-0dd1b90688a7.png)

Then click next and give your virtual Machine a relevant name.In my case, I am naming it DOUBLEU_Ubuntu like the name i gave it to my Ubuntu OS.

![image](https://user-images.githubusercontent.com/85865681/182914908-572ed454-891b-47fa-8d4a-6372da3f9316.png)

You have to select the size of the virtual hard disk.I will allocate 100 GB but you can choose whatever size you want, just make sure it’s more than 20 GB as recommended.

![image](https://user-images.githubusercontent.com/85865681/182915009-8a92c648-3a85-4c5f-8899-73761d62ca00.png)

Now we finished the simple installation as shown:

![image](https://user-images.githubusercontent.com/85865681/182915052-4c7856ca-29e7-4e64-a38e-a949b7434d5e.png)


### Step 6 : Run Ubuntu using Vmware Workstation

Click ‘Power on this virtual machine’ to start the installation.

![image](https://user-images.githubusercontent.com/85865681/182915091-9b3da842-2c6c-4a0a-b64e-b7260bf04c8b.png)
![image](https://user-images.githubusercontent.com/85865681/182915403-f8d29b38-8d8d-4c1b-ae14-c39f6e98c463.png)

### Step 7 : Install Ubuntu 22.04 LTS Desktop

Choose Keyboard Layout 

By default, the system will select English and English.

When you’re ready, click Continue.

![image](https://user-images.githubusercontent.com/85865681/182915574-1378e198-ee5f-474f-827d-1c4c80b9c8db.png)

Choose Starting Applications

* **Normal Installation** – This is the full Ubuntu Desktop experience, with office software, games, and media players.
* **Minimal Installation** – Choose this to save disk space, especially if you won’t be using media players or productivity software.

You’ll also be asked to confirm other options:

* **Download updates while installing Ubuntu** – This does the work of downloading large package files during the installation. Once the installation finishes, the packages will be ready to apply as updates.
* **Install third-party software for graphics and Wi-Fi hardware and additional media formats** – Some hardware, like graphics cards and wi-fi cards, do not have open-source driver support.Also, some media formats, such as .wmv, do not fall under the GPL license.If you need support for these, you’ll need to agree to additional terms of use.

![image](https://user-images.githubusercontent.com/85865681/182915779-13ebba39-3052-40c7-a5f0-efa78b9a7842.png)

Choose the installation type

Here in the installation type window,

If your system currently has no operating systems, the installer will provide the following two options. You can choose any option that suits to you:

* **Erase disk** – Choosing this option will delete everything in your system.There is also additional option called “Advanced Features” that allows you to choose the following three options.
  * Use LVM with the new Ubuntu installation – If you want to resize, add, modify, take snapshot partitions, choose this option.
  * Encrypt the new installation for security – This option lets you to encrypt your Ubuntu system. You will need to choose a security key in the next wizard if you choose this option.
  * EXPERIMENTAL – Erase disk and use ZFS.
* **Something else** – It allows you to manually partition the hard drive yourself. You can set the custom size for each partition. It is opt for dual boot with Windows and/or other OS.

I go with the first option – Erase disk. “keep the default setting as it is and click on Install Now”.

![image](https://user-images.githubusercontent.com/85865681/182916331-9bc5d266-b5fb-42b1-9c81-f9329fe0cf1a.png)

You will see the list of changes that will be made to the disks. If this is OK, click “Continue” or click “Go Back” to make further changes.

![image](https://user-images.githubusercontent.com/85865681/182916364-f1e62ac9-2b10-4e41-a4bd-239c526b7792.png)

Choose the your country.
![image](https://user-images.githubusercontent.com/85865681/182916447-7e33874a-879b-4173-923e-e656c5227a72.png)

The setup of who are you.

you’ll need to configure a user account. Fill in the following fields:

* **Name** : Your actual name.
* **Computer name** : This is the hostname or network name.
* **Username** : The user account name you want to use.
* **Password** : Enter and confirm a strong password – the installer will automatically evaluate your password strength.
* **Log in automatically** : This is not recommended for publicly accessible servers.
* **Require my password to log in** : This is recommended for publicly accessible servers.

Click **Continue** to install Ubuntu.

The Ubuntu 22.04 installation will start now.

![image](https://user-images.githubusercontent.com/85865681/182916562-0c68049f-6996-432a-ab34-18210f3eb394.png)

![image](https://user-images.githubusercontent.com/85865681/182916766-a98d0cc8-f15e-4e1a-9573-24f9c4fea2ab.png)


### Step 8 : Finish



Well, that’s the end of our guide. I hope this article will help you install Ubuntu 22.04 on Vmware Workstation pro in Windows 10 for Macbook Pro 2013.


