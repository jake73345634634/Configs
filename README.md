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

$\color{Yellow}{\textsf{Note: It may look complete at points, but do NOT press anything or close any windows until you see a SetupComplete.txt file on the desktop.}}$

<h4>Post-Installation</h4>

- License Nessus
- Add Nessus plugins
- License BurpSuite
- Add BurpSuite extensions

---
<h4>What's Included?</h4>

<h5>TODO Sort all of this into categories</h5>

- WinGet
- Office 365
- WSL
- Docker
- SysInternals
- Wireguard
- 7zip
- Git
- Greenshot
- mRemoteNG
- Wireshark
- VirtualBox
- Insomnia
- Spotify
- Bloodhound
- Nuclei
- BBOT
- CyberChef
- Mimikatz
- Rubeus
- Seatbelt
- Nuclei Templates
- Nuget

<h5>Text Editors</h5>

- Visual Studio
- Visual Studio Code

<h5>Network Testing</h5>

- Nmap
- Nessus

<h5>Web Application Testing</h5>

- BurpSuite Professional

<h5>Active Directory Testing</h5>

- RSAT
- SharpHound
- RustHound-CE
- Certipy
- bloodyAD

<h5>Azure Testing</h5>

- Azure CLI
- AADInternals
- AzureHound
- Azure Storage Explorer

<h5>Kubernetes Testing</h5>

- Kubernetes RBAC Audit

<h5>Obfuscation</h5>

- InvisibilityCloak
- yetAnotherObfuscator
- Invoke-Argfuscator

<h5>Languages</h5>

- Python
- NodeJS
- Go
- JQ

<h5>Databases</h5>

- Postgres
- Neo4j

---
<h4>TODO</h4>

- [ ] Add shortcuts for all tools that can be ran on this host
- [ ] Add VMWare download and checksum verification
- [ ] Add Kali VM download
- [ ] Add-WindowsCapability -Online -Name Rsat.Dns.Tools~~~~0.0.1.0
- [ ] Make everything into functions for better readability
- [ ] Make Docker and Bloodhound run on start
- [ ] License BurpSuite and Nessus
- [ ] Add BurpSuite extensions and Jython
- [ ] Add Nessus plugins
- [ ] Figure out how to install Spotify via WinGet as it requires user context, not administrative context
- [ ] Add capabilities for "applications"
- [ ] Create better and consistent logs for everything
- [ ] Update the RunOnce section of the script to not... be like that
- [ ] Check everything is installed Mimikatz, Rubeus, Seatbelt, Certipy compilation
- [ ] Install NetExec via Pipx
