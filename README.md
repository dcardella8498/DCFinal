# DCFinal

This repository contains Ansible playbooks for automation of various tasks, both within Linux and Windows

Windows:
- Installs Firefox, Chrome, Office 365, and VLC
    - Reboots when necessary
- Opens relevant ports and turns on Real-Time Protection in Windows Defender
- Enables bitlocker and generates recovery keys. Securely stores recovery keys.
- Collects and displays CPU, RAM, and disk utilization information.
- Installs Windows Updates and reboots if necessary.

Linux: 
- Installs and configures a Nginx webserver, accessible on ports 80 and 443
- Configures firewall rules allowing incoming traffic on ports 80 and 443
- Installs and configures email server software.
   - Configures user accounts
- Installs and configures FreeRADIUS server
