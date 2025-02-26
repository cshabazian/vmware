# vmware
Scripts, playbooks, etc. I have that works with vmware.


### To load esxcli-update on an internet connected ESXi server:    
`wget --no-check-certificate https://raw.githubusercontent.com/cshabazian/vmware/refs/heads/main/esxcli-update -O /sbin/esxcli-update`  
`chmod 555 /sbin/esxcli-update`   
*ESX requires the --no-check-certificate in order to run*
