# Modern HoneyNet (MHN) Adapted Installation
Ubuntu 20.04 compatible. <br>
This repo has been originally forked from https://github.com/pwnlandia/mhn, which does NOT support Ubuntu 20.04. <br>
Ubuntu 20.04 uses Python 3 to install its modules. However, the old repository of Modern HoneyNet uses Python 2 and introduces compatibility issues. <br>
This adaptation modifies the installation files to be compatible with Python 3. <br>

Step 1: Install MHN <br>
```
$ cd /opt/
$ sudo git clone https://github.com/shreyass-prem/CS166FinalProject.git
$ cd mhn/
```

Step 2: Run the following script to complete the installation. <br>
```
$ sudo ./install.sh
```

Step 3: Configuration:
```
===========================================================
MHN Configuration
===========================================================
Do you wish to run in Debug mode?: y/n n
Superuser email: YOUR_EMAIL@YOURSITE.COM
Superuser password: 
Server base url ["http://1.2.3.4"]: 
Honeymap url ["http://1.2.3.4:3000"]:
Mail server address ["localhost"]: 
Mail server port [25]: 
Use TLS for email?: y/n n
Use SSL for email?: y/n n
Mail server username [""]: 
Mail server password [""]: 
Mail default sender [""]: 
Path for log file ["mhn.log"]:
```

This repository contains visualization code to display statistics about the cyber-attackers. The data is specific to the deployed honeypots in our experiments.
