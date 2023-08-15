# Kali-initial-setup




<!-- 
===============================================================================================================================================================
===============================================================================================================================================================
Programming Tools
===============================================================================================================================================================
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Programming Tools </summary>

Programming Tools
---------------------------------------------------------------------------------------------------------------------------------------------------------------

- Update the Package Lists
First, update the package lists to ensure you have the latest information:
```bash
sudo apt-get update
```
- Install C and C++
You can install the GCC compiler for C and C++ using the following command:
```bash
sudo apt-get install build-essential
```
- Install C#
For C#, you can install Mono, which is an open-source implementation of Microsoft's .NET Framework.
```bash
sudo apt install mono-devel
```
- Install Java
You can install Java's OpenJDK with:
```bash
sudo apt-get install default-jdk
```
- Install Python
Python is likely already installed on Kali Linux, but you can ensure you have it with:
```bash
sudo apt install -y python3 python3-pip
```
- Install Visual Studio Code
```bash
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo gpg --dearmor -o /usr/share/keyrings/ms-archive-keyring.gpg

echo "deb [arch=amd64 signed-by=/usr/share/keyrings/ms-archive-keyring.gpg] https://packages.microsoft.com/repos/code stable main" | sudo tee /etc/apt/sources.list.d/ms-vscode.list > /dev/null

sudo apt update
sudo apt install code
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>

`Install C, C++, C#, Java, Python and VS-Code:`
```bash
sudo apt-get update
sudo apt-get install build-essential
sudo apt install mono-devel
sudo apt-get install default-jdk
sudo apt install -y python3 python3-pip
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo gpg --dearmor -o /usr/share/keyrings/ms-archive-keyring.gpg
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/ms-archive-keyring.gpg] https://packages.microsoft.com/repos/code stable main" | sudo tee /etc/apt/sources.list.d/ms-vscode.list > /dev/null
sudo apt update
sudo apt install code
```




<!-- 
===============================================================================================================================================================
===============================================================================================================================================================
Penetration Tools
===============================================================================================================================================================
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Penetration Tools </summary>

Penetration Tools
---------------------------------------------------------------------------------------------------------------------------------------------------------------
### `Nmap` (Network Mapper):
```bash
sudo apt install nmap
```
### `Wireshark` (Network Protocol Analyzer):
```bash
sudo apt install wireshark
```
### `Metasploit Framework` (Penetration Testing Framework):
```bash
sudo apt install metasploit-framework
```
### `Aircrack-ng` (Wireless Network Security Assessment Tool):
```bash
sudo apt install aircrack-ng
```
### `Nikto` (Web Server Scanner):
```bash
sudo apt install nikto
```
### `Hashcat` (Password Recovery and Cracking Tool):
```bash
sudo apt install hashcat
```
### `Hydra` (Password Cracking Tool):
```bash
sudo apt install hydra
```
### `SQLMap` (SQL Injection and Database Penetration Testing Tool):
```bash
sudo apt install sqlmap
```
### `Gobuster` (Directory/File Brute-Force Tool):
```bash
sudo apt install gobuster
```
### `Sublist3r` (Subdomain Enumeration Tool):
```bash
sudo apt install sublist3r
```
### `Dirb` (Directory Brute-Forcing Tool):
```bash
sudo apt install dirb
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>

`Install all penetration tools that were listed:`

```bash
sudo apt-get update
sudo apt install nmap wireshark metasploit-framework aircrack-ng nikto hashcat hydra sqlmap gobuster sublist3r dirb
```




<!-- 
===============================================================================================================================================================
===============================================================================================================================================================
Useful Utilities 
===============================================================================================================================================================
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Useful Utilities </summary>

Useful Utilities
---------------------------------------------------------------------------------------------------------------------------------------------------------------

### [`Guake`](https://github.com/Guake/guake) (A drop-down terminal emulator with quick access):
```https://github.com/lpereira/hardinfo
sudo apt install guake
xfce4-session-settings
```
- In the `Session and Startup` window, go to the `Application Autostart` tab.
- Click on the `Add` button to add a new startup application.
- In the `Add Application` dialog, provide the necessary information:
  - Name: Guake (or any desired name)
  - Description: Terminal dropdown
  - Command: guake
- Click "OK" to save the changes.

### [`Flameshot`](https://github.com/flameshot-org/flameshot) (A Powerful Screenshot Tool):
```
sudo apt install flameshot
xfce4-session-settings
```
- In the `Session and Startup` window, go to the `Application Autostart` tab.
- Click on the `Add` button to add a new startup application.
- In the `Add Application` dialog, provide the necessary information:python --version

  - Name: Flameshot (or any desired name)
  - Description: Screenshot util
  - Command: flameshothttps://github.com/lpereira/hardinfo
- Click "OK" to save the changes.

### [`Hardinfo`](https://github.com/lpereira/hardinfo) (System information and benchmarking utility):
```
sudo apt install hardinfo
hardinfo
```
### `Grub customizer` (A graphical tool for customizing the GRUB bootloader):
```
sudo apt install grub-customizer
sudo grub-customizer
```
### [`Bleachbit`](https://github.com/bleachbit/bleachbit) (System Cleaner):
```bash
sudo apt install bleachbit
```
### [`Gufw`](https://github.com/costales/gufw) (Uncomplicated Linux Firewall):
```bash
sudo apt install gufw
```
---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>

`Install all the packages that were listed:`

- For XFCE Desktop Env:
```bash
sudo apt-get update
sudo apt install guake flameshot hardinfo grub-customizer bleachbit gufw
mkdir -p ~/.config/autostart/
echo -e '[Desktop Entry]\nEncoding=UTF-8\nType=Application\nName=Guake\nExec=guake\nComment=Terminal dropdown\nOnlyShowIn=XFCE;\nRunHook=0\nStartupNotify=false\nTerminal=false\nHidden=false' > ~/.config/autostart/guake.desktop
echo -e '[Desktop Entry]\nEncoding=UTF-8\nType=Application\nName=Flameshot\nExec=flameshot\nComment=Screenshot util' > ~/.config/autostart/flameshot.desktop
```

- For GNOME Desktop Env:
```bash
sudo apt-get update
sudo apt install guake flameshot hardinfo grub-customizer bleachbit gufw
mkdir -p ~/.config/autostart/
echo -e '[Desktop Entry]\nType=Application\nName=Guake\nExec=guake\nComment=Terminal dropdown\nX-GNOME-Autostart-enabled=true' > ~/.config/autostart/guake.desktop
echo -e '[Desktop Entry]\nType=Application\nName=Flameshot\nExec=flameshot\nComment=Screenshot util\nX-GNOME-Autostart-enabled=true' > ~/.config/autostart/flameshot.desktop
```

- For KDE Desktop Env:
```bash
sudo apt-get update
sudo apt install guake flameshot hardinfo grub-customizer bleachbit gufw
mkdir -p ~/.config/autostart-scripts/
echo -e '#!/bin/sh\nexec guake' > ~/.config/autostart-scripts/guake.sh
echo -e '#!/bin/sh\nexec flameshot' > ~/.config/autostart-scripts/flameshot.sh
chmod +x ~/.config/autostart-scripts/guake.sh ~/.config/autostart-scripts/flameshot.sh
```



