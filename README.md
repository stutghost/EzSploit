## :gear: EzSploit

![](https://img.shields.io/badge/Python-3-yellow)
![](https://img.shields.io/badge/platform-KaliLinux%20%7C%20ParrotOS%20%7C%20Termux-blue)
![](https://img.shields.io/github/stars/stutghost/EzSploit)
[![](https://img.shields.io/github/followers/stutghost?label=follow&style=social)](https://github.com/stutghost)
![](https://badges.frapsoft.com/os/v1/open-source.svg?v=102)


#### EzSploit is a tool capable of creating a RAT currently undetectable by Windows Defender, but possible detection by other Anti-Virus. It also has the ability to create RAT's for MacOS and Linux both written in Bash, for kernel compatibility reasons and for their light size, the RAT's are super light not even 800B.

#### It will not be possible to use the RAT if the target is under DDoS attack.

<!---
<br>

## :rocket: Update Avaliable v2.0
-->

<br>

## :toolbox: RAT Compatibility

- Windows
    * Windows 8 (x64)
    * Windows 10 (x64/x86)
    * Windows 11 (x64/x86)

- MacOS
    * Mac Catalina
    * Mac Big Sur
    * Mac Monterey
    * Mac Ventura
    * Other Versions...
    
- Linux
    * Ubuntu
    * Debian
    * Fedora
    * Mint
    * Other Versions...

- Servers
    * Linux Servers
    * Windows Servers (Up to 2016)

<br>

## :camera: Screenshots 
![](https://github.com/stutghost/EzSploit/blob/main/README/ScreenShot-01.png)
![](https://github.com/stutghost/EzSploit/blob/main/README/ScreenShot-02.png)

---

<br>

<h2><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg", width="25", height="25"/> Linux Installation</h2>

kali@kali:~$ ```sudo apt update``` | Update all repositories

kali@kali:~$ ```sudo apt install git python3 python3-pip -y``` | Install Git, Python3 and Pip3

kali@kali:~$ ```git clone https://github.com/stutghost/EzSploit.git``` | Download EzSploit Repository

kali@kali:~$ ```cd EzSploit``` | Go to EzSploit Folder

kali@kali:~$ ```python3 linux_install.py``` | Run the Script Installer

kali@kali:~$ ```./ezsploit``` | Run the Script


<br>


<h2><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/android/android-original.svg", width="25", height="25"/> Termux Installation</h2>

~$ ```pkg update``` | Update all repositories

~$ ```pkg install git python -y``` | Install Git and Python

~$ ```git clone https://github.com/stutghost/EzSploit.git``` | Download EzSploit Repository

~$ ```cd EzSploit``` | Go to EzSploit Folder

~$ ```python termux_install.py``` | Run the Script Installer

~$ ```./ezsploit``` | Run the Script


<br>


<h2><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg", width="25", height="25"/> Windows Installation, using WSL</h2>

##### Run Powershell as Administrator!

PS C:\Users\unknown> ```enable-WindowsOptionalFeature -Online -FeatureName Microsoft-Windows-Subsystem-Linux``` | Enable Linux Subsystem Feature 

**Reboot**

PS C:\Users\unknown> ```dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart``` | Enable Virtual Machine Platform Feature

PS C:\Users\unknown> ```dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart``` | Enable WSL

**Reboot**

Download WSL Package - https://aka.ms/wsl2kernel

PS C:\Users\unknown> ```wsl --set-default-version 2``` | Set WSL2 to Default Choice

Install **Kali linux** on **Windows Store**

kali@kali:~$ ```sudo apt update``` | Update all repositories

kali@kali:~$ ```sudo apt install git python3 python3-pip -y``` | Install Git, Python3 and Pip3

kali@kali:~$ ```git clone https://github.com/stutghost/EzSploit.git``` | Download EzSploit Repository

kali@kali:~$ ```cd EzSploit``` | Go to EzSploit Folder

kali@kali:~$ ```python3 linux_install.py``` | Run the Script Installer

kali@kali:~$ ```./ezsploit``` | Run the Script
