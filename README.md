<h3>🎁 Configs</h3>

---
✨ A list of configuration files used to build a Windows 11 penetration testing image.

---
<h4>Requirements</h4>

An official Windows 11 installation USB. See [here](https://www.microsoft.com/en-us/software-download/windows11) to get started.

---
<h4>Usage</h4>

- Download `autounattend.xml` into the root of your installation USB (you do not need the rest of this repository).
- Boot into the USB. Et voilà.
    - You will be asked to select your language and keyboard localisation, but thereafter is completely unattended.

$\color{Yellow}{\textsf{Note: Wi-Fi is not supported. You must use a wired connection. Ensure you are wired in prior to booting into the USB.}}$

$\color{Yellow}{\textsf{Note: It may look complete at points, but do NOT press anything or close any windows until you see a README.md file on the desktop.}}$

<h4>Post-Installation</h4>

- License Nessus
- Add Nessus plugins
- License BurpSuite
- Add BurpSuite extensions

---
<h4>TODO</h4>

- [ ] Add GNS3 and images for Cisco switches and routers, Fortinets, Dells
- [ ] Change "Config" folder location to be "Information"
- [ ] Create "Config" folder in this repo for... config
- [ ] Install default tools for Kali WSL
- [ ] Add shortcuts for all tools that can be ran on this host
- [ ] Add VMWare download and checksum verification
- [ ] Add Kali VM download
- [ ] Make Docker and Bloodhound run on start
- [ ] License BurpSuite and Nessus
- [ ] Add BurpSuite extensions and Jython
- [ ] Add Nessus plugins
- [ ] Figure out how to install Spotify via WinGet as it requires user context, not administrative context
- [ ] Create better and consistent logs for everything
- [ ] Check everything is installed Mimikatz, Rubeus, Seatbelt, Certipy compilation
- [ ] Install NetExec via Pipx
