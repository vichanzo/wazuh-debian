# Wazuh-Ubuntu
This is a place to keep my notes and scripts on installing Wazuh to Docker

These are only my notes if they help you, then great - but don't expec all things to work perfectly.


```
sudo apt update
sudo apt install vim curl apt-transport-https unzip wget libcap2-bin software-properties-common lsb-release gnupg2
```

```
curl -sO https://packages.wazuh.com/4.3/wazuh-install.sh
sudo bash ./wazuh-install.sh -a
```

Notes - it does not work on Debian 12 in a container.  Try again on Ubuntu 22.04

Reference:
https://computingforgeeks.com/how-to-install-wazuh-server-on-ubuntu

