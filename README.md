# Personal Windows Stash
### **Windows Activation with [MAS](https://github.com/massgravel/Microsoft-Activation-Scripts/releases/tag/1.6)** <sub> including MSOffice <sub/>

```
irm https://get.activated.win | iex
```
-----------------
### **System Optimization**
 [WindowsPowertools](https://github.com/windows-powertool/Powertool)
```
iwr -useb tool.windowpowertool.workers.dev | iex
```
 [Windows 10 Debloater](https://github.com/ChrisTitusTech/winutil)
```
irm https://christitus.com/win | iex
```

### Create autounattend.xml (perform unattended installations of both Windows 10 and Windows 11)

### [schneegans.de](https://schneegans.de/windows/unattend-generator/)


---------------

### Windows Diagnostics, Repair & Troubleshooting
<details>
<summary><strong>open</strong></summary>
 
**System File Checker - Repair corrupted Windows files · Administrator**
```cmd
sfc /scannow
```
**DISM ScanHealth - Thorough corruption scan · Administrator**

```cmd
DISM /Online /Cleanup-Image /ScanHealth
```

**DISM RestoreHealth - Repair Windows component store · Administrator**

```cmd
DISM /Online /Cleanup-Image /RestoreHealth
```


**CHKDSK - Scan filesystem for errors · Administrator**

```cmd
chkdsk C: /scan
```

**CHKDSK - Repair filesystem errors · Administrator**

```cmd
chkdsk C: /f
```
**Windows Memory Diagnostic - Check RAM for problems**

```cmd
mdsched.exe
```

**Overwrite deleted-data free space on C:**

```cmd
cipher /w:C:\
```

</details>

----------

### **Virus Removal**

### [Tron Script](https://github.com/bmrf/tron)

-----------
### **Bypass Microsoft sign it at setup (OOBE)**
> hit **Shift+F10** during setup to open command prompt and enter the code below
```
oobe\bypassnro
```
or 
```
start ms-cxh:localonly
```
------------------

------



<summary>
Package Managers
</summary>

|Website    |Download/Installation| Additional Links |
|-----------|-------------|-------------|
|[Winget](https://winstall.app/)|[Winget Github](https://github.com/microsoft/winget-cli/releases/tag/v1.4.10173)
|[Scoop](https://scoop.sh)|[Scoop Github](https://github.com/ScoopInstaller/Install#readme) 
|[PowerShell Gallery](https://www.powershellgallery.com/)|
|[Chocolatey](https://chocolatey.org/)| [Chocolatey Install](https://chocolatey.org/install)
|[Crates(Cargo)](https://crates.io)| [Cargo Install](https://doc.rust-lang.org/cargo/getting-started/installation.html)| [Awesome Rust](https://crates.io/crates/awesome-rust)
| [PyPI(Python)](https://pypi.org/)
------------
</details>


<details>
<summary>
Fonts
</summary>

### [all Nerdfonts](https://www.nerdfonts.com/font-downloads)
My favourite:
- [Hack](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/Hack.zip)
- [MesloLG](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/Meslo.zip)
- [JetBrainsMono](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/JetBrainsMono.zip)
- [Terminess](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.0.1/Terminus.zip)
----------
</details>


<details>
<summary>
Discord Music Bot
</summary> 

### [Source](https://just-some-bots.github.io/MusicBot/installing/windows/)

### Installation
1. Install [Python3.8](https://www.python.org/ftp/python/3.8.10/python-3.8.10-amd64.exe)
    - During the setup, tick Install **launcher for all users (recommended)** and **Add Python 3.8 to PATH** when prompted
2. Install [Git For Windows](http://gitforwindows.org/)
    - During the setup, tick **Git from the command line and also 3rd-party software, Checkout Windows-style, commit Unix-style endings**, and **Use MinTTY (the default terminal MSYS2)**.
    - Open Git Bash by right-clicking an empty space inside of a folder (e.g My Documents) and clicking **Git Bash here**
    - Run this in the command window that opens.
    ```
    git clone https://github.com/Just-Some-Bots/MusicBot.git MusicBot -b master 
    ```
### After doing that, a folder called MusicBot will appear in the folder you opened Git Bash in. Configure your bot, then run update.bat to update your dependencies, then run.bat to start the MusicBot.

---
</details>    
    

<details>

<summary>
Other Useful Stuff
</summary>

### Rename a folder to this for shortcuts to most windows settings. 

```
Magic.{ED7BA470-8E54-465E-825C-99712043E01C}
```
-----------
</details>
