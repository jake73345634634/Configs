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

$\color{Yellow}{\textsf{Note: It may look complete at points, but do close any windows until you see a README.md file on the desktop.}}$

<h4>Post-Installation</h4>

- License Nessus
- Add Nessus plugins
- License BurpSuite

---
<h4>Tools</h4>

| Category | Tool | Method |
|---|---|---|
| Active Directory | BloodHound | Docker |
| Active Directory | bloodyAD | Repository |
| Active Directory | Certipy | Repository |
| Active Directory | Coercer | Repository |
| Active Directory | GPOZaurr | Repository |
| Active Directory | grADus | Repository |
| Active Directory | kerbrute | File |
| Active Directory | ldapdomaindump | Repository |
| Active Directory | mimikatz | Repository |
| Active Directory | OUned | Repository |
| Active Directory | PlumHound | Repository |
| Active Directory | BlueHound | Repository |
| Active Directory | precompiled-binaries | Repository |
| Active Directory | pywhisker | Repository |
| Active Directory | RSAT ActiveDirectory | Capability |
| Active Directory | RSAT DNS | Capability |
| Active Directory | Rubeus | Repository |
| Active Directory | RustHound-CE | Repository |
| Active Directory | ScriptSentry | Repository |
| Active Directory | SharpCollection | Repository |
| Active Directory | SharpHound | Repository |
| Active Directory | Titanis | Repository |
| AWS | AWS CLI | WinGet |
| Azure | AADInternals | Module |
| Azure | Azure CLI | WinGet |
| Azure | AzureHound | Repository |
| Azure | BloodHound | Docker |
| Azure | precompiled-binaries | Repository |
| Azure | Storage Explorer | WinGet |
| Database | DBeaver | WinGet |
| Database | Firebird:5 | WinGet |
| Database | MySQL Workbench | WinGet |
| Database | Neo4J:4.4 | Docker |
| Database | Postgres:16 | Docker |
| Database | SQL Server Management Studio | WinGet |
| Database | SQLite Browser | WinGet |
| Evasion | deoptimizer | Repository |
| Evasion | InvisibilityCloak | Repository |
| Evasion | Invoke-Argfuscator | Module |
| Evasion | yetAnotherObfuscator | Repository |
| Kali WSL | Evil-WinRM | APT |
| Kali WSL | Impacket | APT |
| Kali WSL | NetExec | APT |
| Kali WSL | proxychains4 | APT |
| Kali WSL | Responder | APT |
| Firewall | vigiLANs | Repository |
| Kubernetes | Kubernetes-RBAC-Audit | Repository |
| Linux | Chisel | File |
| Linux | copyFail30 | Repository |
| Linux | Ligolo-ng (agent) | File |
| Linux | LinPEAS | File |
| Linux | pspy | File |
| Network | BBOT | Docker |
| Network | ffuf | File |
| Network | Ligolo-ng (proxy) | File |
| Network | Nessus | WinGet |
| Network | Nmap | WinGet |
| Network | Nuclei | Docker |
| Network | OpenSSH Server | Capability |
| Network | sqlmap | Repository |
| Network | sslscan | File |
| Network | WireShark | WinGet |
| Resources | CyberChef | Docker |
| Resources | DefaultCreds-cheat-sheet | Repository |
| Resources | Hashcat | File |
| Resources | Jython | File |
| Resources | nuclei-templates | Repository |
| Resources | rockyou.txt | Repository |
| Resources | SecLists | Repository |
| Resources | username-anarchy | Repository |
| Resources | Win11-Pentest | Repository |
| Reversing | DIE | WinGet |
| Reversing | dnSpy | WinGet |
| Reversing | ILSpy | WinGet |
| Reversing | JD-GUI | WinGet |
| Web Application | Burp Suite Professional | WinGet |
| Web Application | Insomnia | WinGet |
| Web Application | auth-analyser | File |
| Web Application | backslash-powered-scanner | File |
| Web Application | error-message-checks | File |
| Web Application | param-miner | File |
| Web Application | js-miner | File |
| Web Application | retire-js | File |
| Web Application | java-deserialisation-scanner | File |
| Web Application | json-web-tokens | File |
| Web Application | inql-graphql-scanner | File |
| Web Application | http-request-smuggler | File |
| Web Application | 403-bypasser | File |
| Web Application | 429-bypasser | File |
| Web Application | active-scan-plus-plus | File |
| Web Application | additional-csrf-checks | File |
| Web Application | additional-scanner-checks | File |
| Windows | Chisel | File |
| Windows | LaZagne | Repository |
| Windows | Ligolo-ng (agent) | File |
| Windows | mimikatz | Repository |
| Windows | precompiled-binaries | Repository |
| Windows | Rubeus | Repository |
| Windows | Seatbelt | Repository |
| Windows | SharpCollection | Repository |
| Windows | SharpHound | Repository |
| Windows | SysInternals | WinGet |
| Windows | Titanis | Repository |
| Windows | Whisker | Repository |
| Windows | WinPEAS | File |
| General | 7zip | WinGet |
| General | Firefox | WinGet |
| General | Git | WinGet |
| General | Go | WinGet |
| General | Greenshot | WinGet |
| General | JQ | WinGet |
| General | KeePass | WinGet |
| General | Make | WinGet |
| General | mRemoteNG | WinGet |
| General | NodeJS | WinGet |
| General | Office | WinGet |
| General | OpenJDK:14 | WinGet |
| General | OpenVPN | WinGet |
| General | Python 3.7-3.13 | WinGet |
| General | Spotify | WinGet |
| General | VirtualBox | WinGet |
| General | Visual Studio 2022 | WinGet |
| General | Visual Studio Code | WinGet |
| General | WireGuard | WinGet |
| General | YubiKey Manager | WinGet |

---
<h4>TODO</h4>

- Coercer doesn't work - some netifaces error
- Add VMWare download and checksum verification
- License BurpSuite and Nessus
- Add Nessus plugins
- Figure out how to install Spotify via WinGet as it requires user context, not administrative context
- Create better and consistent logs for everything
- Check everything is installed Mimikatz, Rubeus, Seatbelt, Certipy compilation
