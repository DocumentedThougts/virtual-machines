# Installation of Guest Additions

**Reason:** VirtualBox Guest Additions enhance virtual machine performance and usability by providing features like seamless mouse integration, optimized graphics, and shared clipboard functionality. They allow for better data transfer, efficient window management, and improved network performance, making it easier for administrators to manage and interact with virtual environments. These additions ultimately make the virtual machine experience more user-friendly and efficient.

Open VirtualBox Manager and power on your VM with Windows 11 Operating system

![power-on-vm](./images/power-on-vm.png)

Next use your user and password to login

![success-login](./images/success-login.png)

In your window of your VM select submenu **Devices** and option **Insert Guest Additions CD Image** 

![devices-submenu](./images/devices-submenu.png)

If nothing is happening, open **File Explorer** and you should see similar to image below

![cd-drive](./images/cd-drive.png)

Open it and find **VBoxWindowsAdditions-Amd64.exe**, and you need to run it as administrator

![additions-amd64](./images/additions-amd64.png)

In Setup Manager I will use default settings, so just click **Next**

![additions-wizard](./images/additions-wizard.png)

After completion of installation it will ask to reboot the system.