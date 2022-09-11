# Versionamento-da-atividade-Linux

## Version 1.0

The installation of Oracle Linux 8.6 is complete. The root user has been logged in.

Snapshot File: {e5bd9d5d-5f5c-42ca-bfae-2ec33de45d8a}.vhd

## Version 2.0

VM VLAN configured in BRIGDE mode. Made the necessary adjustments. 

Changes to /etc/sysconfig/network-scripts/ifcfg-enp0s3 and /etc/resolv.conf files.

#### A static IP has been configured for the network, IP: 192.168.0.115. 

The /etc/sysconfig/network-scripts/ifcfg-enp0s3 file has changed. Switching from DHCP mode to static. 

Adding static IP 192.168.0.115, netmask 255.255.255.0 and gateway 192.168.0.1.

The /etc/resolv.conf file has changed. Adding Google DNS 8.8.8.8 and 8.8.4.4.

Snapshot File: {c16a8951-a953-4ce4-9bce-12d45735a9d0}.vhd

### Version 2.1

Updated virtual machine. Installing and updating packages.

Snapshot File: {4de35b40-d10d-4481-8fea-80e1b968189d}.vhd

## Version 3.0

Trust relationship between VMs established.

Changes to the /root/.ssh directory. "authorized_keys" file created on both machines to store the keys.

Snapshot Files: 

VM1 (Oracle Linux 1) :{9d330f06-d8ae-4966-97ea-4398f3ca850a}.vhd  IP: 192.168.0.200

VM2 (Oracle-Linux) : {397536df-3c06-4298-a0c4-c2f711dd6182}.vhd   IP:192.168.0.115

### Version 3.1

Bug fixes. File sharing via samba server.

Changes to the /etc/samba directory. File smb.conf was changed.

Snapshot Files:

VM1 (Oracle Linux 1) : {51fac9a7-1e78-4cfd-abb6-d7481010d502}.vhd    IP: 192.168.0.200

VM2 (Oracle-Linux) : {0dc8ded3-0432-475d-94fa-a2c3241de37b}.vhd   IP:192.168.0.115

### Version 3.2

Updates and bug fixes.

Trust relationship between machines rebuilt.
Changes to the /root/.ssh directory. File "authorized_keys" created on both machines to store the keys.

Snapshot Files:

VM1 (Oracle Linux 1) : {8f49992b-39e8-49b1-a427-4b284e1fec73}.vhd    IP: 192.168.0.200

VM2 (Oracle-Linux) : {0fb75d1b-b455-4798-82cb-1d695bbd30fa}.vhd      IP:192.168.0.115
