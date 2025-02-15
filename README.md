# How to Install Ubuntu Linux: Step-by-Step Guide
## Introduction
Ubuntu is free, fast and user-friendly, It runs very smoothly on old laptops, You don’t need very high specifications to run Ubuntu OS. It’s very secure and has a large open source community to support it.
Follow these steps, and you'll have Ubuntu installed and running in your machine.
## Prerequisites
* Your old laptop with minimum specifications: dual-core processor, 2GB RAM, 25GB free disk space
* A USB drive (minimum 8GB)
* Stable Internet connection
* Create backup of your data
## Step-by-Step Guide
### Step 1: Download Ubuntu ISO
* Download the latest version of Ubuntu Desktop LTS (Long Term Support) ISO file from the official Ubuntu website: https://ubuntu.com/download/
### Step 2: Create a Bootable USB
* Recommended tool to create bootable USB: [Rufus](https://rufus.ie/en)
  *  Launch the **Rufus** tool
  *  Insert your USB Device
  *  Select the USB drive name in Device dropdown
  *  Select ‘**Disk or ISO image**‘ option in Boot selection
  *  Click on **Select** button and locate the iso file downloaded in Step 1
  *  Select ‘**MBR**‘ in Partition scheme and ‘**BIOS** or **UEFI**‘ option in Target System
  *  Add volume name
  *  Click on **Start** button
  *  Click OK on **Warning: ALL DATA ON DEVICE WILL BE DESTROYED**

![2](https://github.com/user-attachments/assets/21fb10b1-18b5-43b9-beb7-1d56f7b38070)

### Step 3: Boot from USB
* Insert the bootable USB drive into your laptop
* Restart the laptop, press the appropriate key (**F10**, **F11**, **F12**, etc depending on your laptop) to access the boot menu
* Select the **USB Storage Device** from Legacy Boot menu option

![2](https://github.com/user-attachments/assets/72543096-a284-493f-96c9-f1b08fcab5e4)

### Step 4: Try Ubuntu and Install
* Choose the “**Try or Install Ubuntu**“ option and press **Enter**

![IMG_4515](https://github.com/user-attachments/assets/6cdfe3e0-a05b-44ff-b784-bba5fa3e7c72)

* After selecting the "**Try or Install Ubuntu**" option and pressing **Enter**, the system will begin preparing Ubuntu for installation.

![Screenshot from 2025-01-31 14-20-19](https://github.com/user-attachments/assets/ad9c1154-c010-4501-a903-c7c9d58c5b7c)

* Once the Ubuntu installer starts, you will be prompted to choose your preferred language. A list of available languages is displayed on the screen. Scroll through the list and select your desired language (e.g., **English**)

![Screenshot from 2025-01-31 14-21-14](https://github.com/user-attachments/assets/d795e6d9-a917-4945-a557-19f2c0852dfa)

* Configuring Accessibility Settings in Ubuntu, In this step of the Ubuntu installation process, you have the option to customize accessibility settings to enhance usability for different needs.

![Screenshot from 2025-01-31 14-21-23](https://github.com/user-attachments/assets/47554da1-5c4b-4ac1-bc45-57669cbc903a)

* Choose the keyboard layout that matches your supported keyboard. You can also click the "**Detect**" button to automatically identify the correct layout

![Screenshot from 2025-01-31 14-21-34](https://github.com/user-attachments/assets/3d29aaa2-6941-451a-b0a9-fc0db9d7ee38)

* Connect to the internet to improve the installation process with compatibility checks and additional software packages

![Screenshot from 2025-01-31 14-22-28](https://github.com/user-attachments/assets/6dd33ab4-a597-4dd7-b543-96ea69a38e3a)

* What would you like to do with Ubuntu? You can either **Try Ubuntu** or **Install Ubuntu.** In my case, I chose "**Install Ubuntu**" directly.

![Screenshot from 2025-01-31 14-22-44](https://github.com/user-attachments/assets/4ad5f030-1b6d-4f2c-9fa3-ad7547f03184)

* Select the Ubuntu Installation Type. At this stage, Ubuntu asks you to choose an installation method based on your preferences and technical expertise. I opted for "**Interactive Installation.**"

![Screenshot from 2025-01-31 14-22-57](https://github.com/user-attachments/assets/35d4bfd7-9f1f-4971-a661-d0738b32008e)

* Choose the **Default Selection** option for the "What apps would you like to install to start with?"

![Screenshot from 2025-01-31 14-23-08](https://github.com/user-attachments/assets/0b69ec37-a488-4e03-a5fb-a95a02018752)

* After selecting the checkbox "Install third-party software for graphics and Wi-Fi hardware," click the **Next** button to proceed.

![Screenshot from 2025-01-31 14-23-21](https://github.com/user-attachments/assets/be0b881a-612b-4da4-9927-ba209ccf423b)

* In Disk Setup and Installation Options step, you configure how Ubuntu will be installed on your disk. Key choices include:
  *  **Install Ubuntu alongside Ubuntu 24.04.1 LTS:** Ideal for dual-booting, allowing you to choose between operating systems at boot.
  *  **Erase disk and install Ubuntu:** Clears the entire disk for a fresh Ubuntu installation (ensure backups are made).
  *  **Advanced features:** Optional settings like encryption or LVM, not enabled by default.
  *  **Manual installation:** For advanced users who want full control over disk partitioning.

After selecting your preferred option, click **Next** to continue

![Screenshot from 2025-01-31 14-23-50](https://github.com/user-attachments/assets/18f223d0-f4fb-49ad-9c63-cdeab7bb0b08)

* In Create Your User Account, you set up your primary login for Ubuntu by providing:
  *  **Your Name:** Your full name for display on the system.
  *  **Your Computer’s Name:** A name to identify your machine on a network.
  *  **Your Username:** Your login name for system operations.
  *  **Password:** A strong password, confirmed for security.
  *  **Require my password to log in:** Ensures password-protected access.
 
After completing these fields, click **Next** to proceed 

![Screenshot from 2025-01-31 14-24-56](https://github.com/user-attachments/assets/9a837705-5258-4a7e-bae8-f08f5ec98b68)

* In Select Your Timezone, you configure your system’s time and date settings:
  *  **Location:** The installer auto-detects your location (e.g., Mumbai, India). You can manually adjust it if needed.
  *  **Timezone:** The appropriate timezone (e.g., Asia/Kolkata) is set based on your location, ensuring accurate time synchronization.

After confirming your settings, click **Next** to proceed

![Screenshot from 2025-01-31 14-25-37](https://github.com/user-attachments/assets/3dcbe642-ec02-461c-80ba-f9bbd910ca34)

* In Review Your Installation Choices, you finalize your setup before installation:
  *  **General:** Confirm disk setup, installation disk, and default applications.
  *  **Security & more:** Check disk encryption and proprietary software settings (both set to “None” here).
  *  **Partitions:** Review created/modified partitions (e.g., sdb1 and sdb2 formatted as ext4 for root). 

If everything is correct, click **Install** to proceed or **Back** to make changes. This step ensures your settings are accurate before installation begins.

![Screenshot from 2025-01-31 19-56-20](https://github.com/user-attachments/assets/7eb1a543-961a-4222-89f3-272f8abab278)

### **Step 5: Congratulations! Ubuntu Linux Has Been Installed on Your Machine**

![123](https://github.com/user-attachments/assets/aeb1b709-7d61-4b24-8ce1-7004b864925b)
