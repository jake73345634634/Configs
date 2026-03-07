<h3>🎁 Windows 11 Pentest Build</h3>

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

$\color{Yellow}{\textsf{Note: Sometimes you have to manually login (no password; just press enter) but do nothing after. I am trying to fix this.}}$

<h4>Post-Installation</h4>

- License Nessus
- Add Nessus plugins
- License BurpSuite
- [Bridge WSL](https://github.com/Unsigned-Char/WSL2HyperVSwitch)

---
<h4>Tools</h4>

<h5>Configuration</h5>

- Repository: Win11-Pentest (this repository)

<h5>Evasion</h5>

- Module: Invoke-Argfuscator
- Repository: InvisibilityCloak
- Repository: yetAnotherObfuscator
- Repository: deoptimizer

<h5>Reversing</h5>

- WinGet: dnSpy
- WinGet: ILSpy
- WinGet: DIE
- WinGet: JD-GUI

<h5>Windows</h5>

- File: Chisel
- File: WinPEAS
- Repository: mimikatz
- Repository: Rubeus
- Repository: Seatbelt
- Repository: precompiled-binaries
- Repository: SharpCollection
- Repository: Titanis
- WinGet: SysInternals

<h5>Linux</h5>

- File: Chisel
- File: LinPEAS

<h5>Kali WSL</h5>

- APT: Impacket
- APT: Responder
- APT: NetExec

<h5>Active Directory</h5>

- Capability: RSAT ActiveDirectory
- Capability: RSAT DNS
- Docker: BloodHound
- Repository: SharpHound
- Repository: RustHound-CE
- Repository: PlumHound
- Repository: BlueHound
- Repository: Certipy
- Repository: bloodyAD
- Repository: ScriptSentry
- Repository: GPOZaurr
- Repository: precompiled-binaries
- Repository: SharpCollection
- Repository: Coercer
- Repository: Titanis

<h5>Network</h5>

- Docker: Nuclei
- Docker: BBOT
- WinGet: Nessus
- WinGet: Nmap
- WinGet: WireShark

<h5>Kubernetes</h5>

- Repository: Kubernetes-RBAC-Audit

<h5>Azure</h5>

- Docker: BloodHound
- Repository: AzureHound
- Module: AADInternals
- Repository: precompiled-binaries
- WinGet: Azure CLI
- WinGet: Storage Explorer

<h5>AWS</h5>

- WinGet: AWS CLI

<h5>Web Application</h5>

- WinGet: Burp Suite Professional
- WinGet: Insomnia

<h5>Database</h5>

- Docker: Postgres:16
- Docker: Neo4J:4.4
- WinGet: Firebird:5
- WinGet: DBeaver
- WinGet: SQL Server Management Studio
- WinGet: MySQL Workbench
- WinGet: SQLite Browser

<h5>Resources</h5>

- Docker: CyberChef
- File: Jython
- File: Hashcat
- Repository: nuclei-templates
- Repository: SecLists
- Repository: DefaultCreds-cheat-sheet
- Repository: username-anarchy
- Repository: rockyou.txt
- WinGet: Visual Studio 2022
- WinGet: Visual Studio Code
- WinGet: Office
- WinGet: WireGuard
- WinGet: OpenVPN
- WinGet: 7zip
- WinGet: Git
- WinGet: Python:3.13
- WinGet: NodeJS
- WinGet: Go
- WinGet: JQ
- WinGet: Greenshot
- WinGet: mRemoteNG
- WinGet: Make
- WinGet: VirtualBox
- WinGet: Spotify
- WinGet: OpenJDK:14
- WinGet: KeePass

---
<h4>TODO</h4>

- [ ] Make sure everything is put into the re-install section (failed to install, config, changes etc.)
- [ ] Add GNS3 and images for Cisco switches and routers, Fortinets, Dells
- [ ] Add VMWare download and checksum verification
- [ ] License BurpSuite and Nessus
- [ ] Add Nessus plugins
- [ ] Figure out how to install Spotify via WinGet as it requires user context, not administrative context
- [ ] Create better and consistent logs for everything
- [ ] Check everything is installed Mimikatz, Rubeus, Seatbelt, Certipy compilation
