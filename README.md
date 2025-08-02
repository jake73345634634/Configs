<h3>🎁 Configs</h3>

---
✨ A list of configuration files used to build a clean Windows 11 image.

---
<h4>Requirements</h4>

An official Windows 11 installation USB. See [here](https://www.microsoft.com/en-us/software-download/windows11) to get started.

---
<h4>Usage</h4>

- Download `autounattend.xml`. You do not need the rest of this repository.
- Navigate [here](https://schneegans.de/windows/unattend-generator) and import the above XML file.
- Scroll down to the `Computer name` section, and replace **JAKE** with your name.
- Scroll down to the `User accounts` section, and replace **Jake** with your name.
- Scroll down to the `WLAN / Wi-Fi setup` section, and replace the XML with your WLAN export.
- At the bottom, click `Download .xml file` and put this file into the root of your installation USB.
- Boot into the USB. Et voilà.
    - You will be asked to select your language and keyboard localisation, but thereafter is completely unattended.

Do NOT press anything or close windows until you see a `SetupComplete.txt` file on the desktop.

Note that changing anything other than what is mentioned above is not supported and may break things.

---
<h4>TODO</h4>

- [ ] Make everything into functions for better readability
- [ ] Make Docker and Bloodhound run on start
- [ ] Add links to Edge bookmarks for Nessus and Bloodhound
- [ ] License BurpSuite and Nessus
- [ ] Add BurpSuite extensions
- [ ] Add Nessus plugins
- [ ] Figure out how to install Spotify via WinGet as it requires user context, not administrative context
- [ ] Add capabilities for "github_applications"
- [ ] Create better and consistent logs for everything
- [ ] Update the RunOnce section of the script to not... be like that
- [ ] Create folders for different phases within Tools, such as Active Directory
