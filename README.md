# Kali-initial-setup

<!-- 
===============================================================================================================================================================
 /$$$$$$$                                                                              /$$                           /$$$$$$$$                  /$$          
| $$__  $$                                                                            |__/                          |__  $$__/                 | $$          
| $$  \ $$ /$$$$$$   /$$$$$$   /$$$$$$   /$$$$$$  /$$$$$$  /$$$$$$/$$$$  /$$$$$$/$$$$  /$$ /$$$$$$$   /$$$$$$          | $$  /$$$$$$   /$$$$$$ | $$  /$$$$$$$
| $$$$$$$//$$__  $$ /$$__  $$ /$$__  $$ /$$__  $$|____  $$| $$_  $$_  $$| $$_  $$_  $$| $$| $$__  $$ /$$__  $$         | $$ /$$__  $$ /$$__  $$| $$ /$$_____/
| $$____/| $$  \__/| $$  \ $$| $$  \ $$| $$  \__/ /$$$$$$$| $$ \ $$ \ $$| $$ \ $$ \ $$| $$| $$  \ $$| $$  \ $$         | $$| $$  \ $$| $$  \ $$| $$|  $$$$$$ 
| $$     | $$      | $$  | $$| $$  | $$| $$      /$$__  $$| $$ | $$ | $$| $$ | $$ | $$| $$| $$  | $$| $$  | $$         | $$| $$  | $$| $$  | $$| $$ \____  $$
| $$     | $$      |  $$$$$$/|  $$$$$$$| $$     |  $$$$$$$| $$ | $$ | $$| $$ | $$ | $$| $$| $$  | $$|  $$$$$$$         | $$|  $$$$$$/|  $$$$$$/| $$ /$$$$$$$/
|__/     |__/       \______/  \____  $$|__/      \_______/|__/ |__/ |__/|__/ |__/ |__/|__/|__/  |__/ \____  $$         |__/ \______/  \______/ |__/|_______/ 
                              /$$  \ $$                                                              /$$  \ $$                                               
                             |  $$$$$$/                                                             |  $$$$$$/                                               
                              \______/                                                               \______/      
===============================================================================================================================================================
-->

<details>
  <summary> :red_circle: Programming Tools </summary>

<br>
<table>
<td>
<details>
  <summary> Selective Installation </summary>

Selective Installation
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
- Install glib
```bash
sudo apt-get install libglib2.0-dev
sudo apt-get install libgtk2.0-dev
```
- Install QT Creator
```bash
sudo apt-get -y install build-essential openssl libssl-dev libssl1.0 libgl1-mesa-dev libqt5x11extras5
sudo apt install qtbase5-dev qt5-qmake qtbase5-dev-tools
sudo apt-get install qtcreator
```

</details>
</table>

`Install C, C++, C#, Java, Python, glib, QT-Creator:`
```bash
sudo apt-get update
sudo apt-get -y install build-essential openssl libssl-dev libssl1.0 libgl1-mesa-dev libqt5x11extras5
sudo apt-get -y install libglib2.0-dev
sudo apt-get -y install libgtk2.0-dev
sudo apt -y install qtbase5-dev qt5-qmake qtbase5-dev-tools
sudo apt-get -y install qtcreator
sudo apt -y install mono-devel
sudo apt-get -y install default-jdk
sudo apt -y install -y python3 python3-pip
```

---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>











<!-- 
===============================================================================================================================================================
 /$$$$$$$                                 /$$                          /$$     /$$                           /$$$$$$$$                  /$$          
| $$__  $$                               | $$                         | $$    |__/                          |__  $$__/                 | $$          
| $$  \ $$ /$$$$$$  /$$$$$$$   /$$$$$$  /$$$$$$    /$$$$$$  /$$$$$$  /$$$$$$   /$$  /$$$$$$  /$$$$$$$          | $$  /$$$$$$   /$$$$$$ | $$  /$$$$$$$
| $$$$$$$//$$__  $$| $$__  $$ /$$__  $$|_  $$_/   /$$__  $$|____  $$|_  $$_/  | $$ /$$__  $$| $$__  $$         | $$ /$$__  $$ /$$__  $$| $$ /$$_____/
| $$____/| $$$$$$$$| $$  \ $$| $$$$$$$$  | $$    | $$  \__/ /$$$$$$$  | $$    | $$| $$  \ $$| $$  \ $$         | $$| $$  \ $$| $$  \ $$| $$|  $$$$$$ 
| $$     | $$_____/| $$  | $$| $$_____/  | $$ /$$| $$      /$$__  $$  | $$ /$$| $$| $$  | $$| $$  | $$         | $$| $$  | $$| $$  | $$| $$ \____  $$
| $$     |  $$$$$$$| $$  | $$|  $$$$$$$  |  $$$$/| $$     |  $$$$$$$  |  $$$$/| $$|  $$$$$$/| $$  | $$         | $$|  $$$$$$/|  $$$$$$/| $$ /$$$$$$$/
|__/      \_______/|__/  |__/ \_______/   \___/  |__/      \_______/   \___/  |__/ \______/ |__/  |__/         |__/ \______/  \______/ |__/|_______/
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Penetration Tools </summary>

<br>
<table>
<td>
<details>
  <summary> Selective Installation </summary>

Selective Installation
---------------------------------------------------------------------------------------------------------------------------------------------------------------

<table>
<td>

`Nmap` (Network Mapper):
```bash
sudo apt install nmap
```
`Wireshark` (Network Protocol Analyzer):
```bash
sudo apt install wireshark
```
`Metasploit Framework` (Penetration Testing Framework):
```bash
sudo apt install metasploit-framework
```
`Aircrack-ng` (Wireless Network Security Assessment Tool):
```bash
sudo apt install aircrack-ng
```
`Nikto` (Web Server Scanner):
```bash
sudo apt install nikto
```
`Hashcat` (Password Recovery and Cracking Tool):
```bash
sudo apt install hashcat
```

<td>

`Hydra` (Password Cracking Tool):
```bash
sudo apt install hydra
```
`SQLMap` (SQL Injection and Database Penetration Testing Tool):
```bash
sudo apt install sqlmap
```
`Gobuster` (Directory/File Brute-Force Tool):
```bash
sudo apt install gobuster
```
`Sublist3r` (Subdomain Enumeration Tool):
```bash
sudo apt install sublist3r
```
`Dirb` (Directory Brute-Forcing Tool):
```bash
sudo apt install dirb
```
`Burp Suite CE` (Web Vulnerability Scanner and Proxy):
```bash
sudo apt install burpsuite
```
</table>
</details>
</table>

`Install all penetration tools that've been listed:`

```bash
sudo apt-get update
sudo apt -y install nmap wireshark metasploit-framework aircrack-ng nikto hashcat hydra sqlmap gobuster sublist3r dirb burpsuite
```

---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>











<!-- 
===============================================================================================================================================================
 /$$   /$$                           /$$                                                               /$$                /$$$$$$   /$$$$$$ 
| $$  | $$                          | $$                                                              | $$               /$$__  $$ /$$__  $$
| $$  | $$  /$$$$$$   /$$$$$$   /$$$$$$$ /$$  /$$  /$$  /$$$$$$   /$$$$$$   /$$$$$$         /$$$$$$$ /$$$$$$   /$$   /$$| $$  \__/| $$  \__/
| $$$$$$$$ |____  $$ /$$__  $$ /$$__  $$| $$ | $$ | $$ |____  $$ /$$__  $$ /$$__  $$       /$$_____/|_  $$_/  | $$  | $$| $$$$    | $$$$    
| $$__  $$  /$$$$$$$| $$  \__/| $$  | $$| $$ | $$ | $$  /$$$$$$$| $$  \__/| $$$$$$$$      |  $$$$$$   | $$    | $$  | $$| $$_/    | $$_/    
| $$  | $$ /$$__  $$| $$      | $$  | $$| $$ | $$ | $$ /$$__  $$| $$      | $$_____/       \____  $$  | $$ /$$| $$  | $$| $$      | $$      
| $$  | $$|  $$$$$$$| $$      |  $$$$$$$|  $$$$$/$$$$/|  $$$$$$$| $$      |  $$$$$$$       /$$$$$$$/  |  $$$$/|  $$$$$$/| $$      | $$      
|__/  |__/ \_______/|__/       \_______/ \_____/\___/  \_______/|__/       \_______/      |_______/    \___/   \______/ |__/      |__/      
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Hardware Stuff </summary>

<br>

- Install Bluetooth services and add em to autostart for XFCE (and propably GNOME) Desktop Env:

```bash
# Install dependencies
sudo apt-get update
sudo apt-get upgrade
sudo apt-get -y install bluetooth bluez bluez-tools rfkill
sudo systemctl enable bluetooth
sudo systemctl start bluetooth
sudo rfkill unblock bluetooth
sudo service bluetooth start
sudo apt-get -y install blueman
# Create autostart directory if it doesn't exist
mkdir -p ~/.config/autostart
# Make sure autostart directory has appropriate permissions
chmod -R 755 ~/.config/autostart
# Add bluetooth to autostart
echo -e '[Desktop Entry]
Type=Application
Exec=bluetooth-applet
Hidden=false
NoDisplay=false
Name=Bluetooth
Comment=Enable Bluetooth at startup' | tee ~/.config/autostart/bluetooth.desktop

```

- Install Pavucontrol (audio device manager) and add it to autostart for XFCE (and propably GNOME) Desktop Env:

_**This one is very optional! In case you're using multiple audio devices!**_

```bash
sudo apt-get install pasystray
mkdir -p ~/.config/autostart
chmod -R 755 ~/.config/autostart

# Add Pavucontrol to autostart
echo "[Desktop Entry]
Name=Pavucontrol
Exec=pavucontrol --start-hidden
Comment=Audio Volume Control
Terminal=false
Type=Application" > ~/.config/autostart/pavucontrol.desktop

# Add Pasystray to autostart
echo "[Desktop Entry]
Name=Pasystray
Exec=pasystray
Comment=PulseAudio System Tray
Terminal=false
Type=Application" > ~/.config/autostart/pasystray.desktop
```

---------------------------------------------------------------------------------------------------------------------------------------------------------------
</details>









<!-- 
===============================================================================================================================================================
 /$$   /$$                      /$$$$$$           /$$       /$$   /$$   /$$     /$$ /$$ /$$   /$$     /$$                          
| $$  | $$                     /$$__  $$         | $$      | $$  | $$  | $$    |__/| $$|__/  | $$    |__/                          
| $$  | $$  /$$$$$$$  /$$$$$$ | $$  \__//$$   /$$| $$      | $$  | $$ /$$$$$$   /$$| $$ /$$ /$$$$$$   /$$  /$$$$$$   /$$$$$$$      
| $$  | $$ /$$_____/ /$$__  $$| $$$$   | $$  | $$| $$      | $$  | $$|_  $$_/  | $$| $$| $$|_  $$_/  | $$ /$$__  $$ /$$_____/      
| $$  | $$|  $$$$$$ | $$$$$$$$| $$_/   | $$  | $$| $$      | $$  | $$  | $$    | $$| $$| $$  | $$    | $$| $$$$$$$$|  $$$$$$       
| $$  | $$ \____  $$| $$_____/| $$     | $$  | $$| $$      | $$  | $$  | $$ /$$| $$| $$| $$  | $$ /$$| $$| $$_____/ \____  $$      
|  $$$$$$/ /$$$$$$$/|  $$$$$$$| $$     |  $$$$$$/| $$      |  $$$$$$/  |  $$$$/| $$| $$| $$  |  $$$$/| $$|  $$$$$$$ /$$$$$$$/      
 \______/ |_______/  \_______/|__/      \______/ |__/       \______/    \___/  |__/|__/|__/   \___/  |__/ \_______/|_______/       
===============================================================================================================================================================
-->
<details>
  <summary> :red_circle: Useful Utilities </summary>

<br>
<table>
<td>
<details>
  <summary> Selective Installation </summary>

Selective Installation
---------------------------------------------------------------------------------------------------------------------------------------------------------------

[`Guake`](https://github.com/Guake/guake) (Drop-down terminal with quick access):
```https://github.com/lpereira/hardinfo
sudo apt install guake
xfce4-session-settings
```
- In the `Session and Startup` window, go to the `Application Autostart` tab.
- Click on the `Add` button to add a new startup application.
- In the `Add Application` dialog, provide the necessary information:
  - Name: Guake
  - Description: Terminal dropdown
  - Command: guake
- Click "OK" to save the changes.

[`Flameshot`](https://github.com/flameshot-org/flameshot) (A Powerful Screenshot Tool):
```
sudo apt install flameshot
xfce4-session-settings
```
- In the `Session and Startup` window, go to the `Application Autostart` tab.
- Click on the `Add` button to add a new startup application.
- In the `Add Application` dialog, provide the necessary information:python --version
  - Name: Flameshot
  - Description: Screenshot util
  - Command: flameshothttps://github.com/lpereira/hardinfo
- Click "OK" to save the changes.

[`Hardinfo`](https://github.com/lpereira/hardinfo) (System info and benchmarking util):
```
sudo apt install hardinfo
hardinfo
```
[`Bleachbit`](https://github.com/bleachbit/bleachbit) (System Cleaner):
```bash
sudo apt install bleachbit
```
[`Gufw`](https://github.com/costales/gufw) (Uncomplicated Linux Firewall):
```bash
sudo apt install gufw
```

</details>
</table>

`Install all the packages that were listed:`

- Install all packages:
```bash
sudo apt-get update
sudo apt -y install guake flameshot hardinfo bleachbit gufw
```

- Include in the autorun for XFCE (and propably GNOME) Desktop Env:
```bash
# Create autostart directory if it doesn't exist
mkdir -p ~/.config/autostart
# Make sure autostart directory has appropriate permissions
chmod -R 755 ~/.config/autostart
# Add guake to autostart
echo -e '[Desktop Entry]
Type=Application
Name=Guake
Comment=terminal emulator
Exec=guake
RunHook=0
StartupNotify=false
Terminal=false
Hidden=false' > ~/.config/autostart/guake.desktop
# Add Flameshot to autostart
echo -e '[Desktop Entry]
Encoding=UTF-8
Type=Application
Name=Flameshot
Exec=flameshot
Comment=Screenshot util' > ~/.config/autostart/flameshot.desktop
```

</details>
