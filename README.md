# vmware
Scripts, playbooks, etc. I have that works with vmware.


### esxcli-update
This script will check for  the latest update available and install it if you wish:   
```
    esxcli network firewall ruleset set -e true -r httpClient  # You can't wget the below if the firewall doesn't allow it
    wget --no-check-certificate https://raw.githubusercontent.com/cshabazian/vmware/refs/heads/main/esxcli-update -O /sbin/esxcli-update  
    chmod 555 /sbin/esxcli-update   
```
    
*ESX requires the --no-check-certificate in order to wget a file from github*
