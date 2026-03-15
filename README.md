# VMware Virtual Network Lab

## Environment
- Windows 10 VM
- Ubuntu (24.04) VM
- Fedora 43 VM
  ### VMWare Environment
![VMware](screenshots/vms_vmware.jpg)

## Network Configuration
Static IP addresses were assigned to each machine.

Example:
Windows  → 192.168.163.11
Ubuntu   → 192.168.163.10
Fedora   → 192.168.163.12

## Connectivity Testing
Network communication verified using ping.

## File Sharing
A Windows shared folder was accessed from Linux using SMB.
### Shared Folder on Windows
![Windows shared folder](screenshots/windows-share.png)
### Accessing the file via Samba on Linux
<p align="center">
  <img src="screenshots/fedora-smb.jpg" width="400" />
  <img src="screenshots/fedora-smb-file.jpg" width="400" />
</p>


## Remote Access
SSH configured between Linux machines for remote administration.
![SSH](screenshots/ssh-login.png)
