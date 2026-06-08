# reticulum-OS
a reticulum network OS based on Debian for raspberry pi
Based on debian 13 (trixie). Included is rnsd, lxmf, nomadnet, and direwolf. lmxd-p starts on boot. config files for rnsd and lxmf are in the standard directories. This OS only includes RF interfaces, rnode and KISS for digirig mobile are configured. The direwolf TCP config is set up at 1200 baud and cp108 ptt for uhf/vhf and digirig lite. Direwolf comfig file is located at /etc/direwolf.conf. Refer to reticulum network website for additional interfaces and modifications to config files.

 Config file locations:
 direwolf: /etc/direwolf conf
 reticulum: /home/rns/.reticulum/config
 lxmf: /home/rns/.lxmf/config
