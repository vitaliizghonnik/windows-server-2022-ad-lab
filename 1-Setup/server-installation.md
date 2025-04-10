# Windows Server 2022 Installation

## Prerequisites

* VMware Workstation 17 Pro 
* Windows Server 2022 ISO file
* Allocated system resources: 4 CPU cores, 6GB RAM, 80GB disk space, Network adapter .

## Steps:

1. Create Virtual Machine with configured system resources.
2. Install Windows Server from an attached ISO file.
3. Configure network settings: 
    
    - Set up static IP to IPv4: 172.16.0.10
    - Subnet mask: 255.255.255.0
    - Preferred DNS: 127.0.0.1 (optionally, it may be set to 172.16.0.10)
    - For the purpose of this lab the default gataway is left blank
    - After installation the type of network communication should be changed to "Host-only".

4. Rename computer, e.g Server2022-DC1, and restart the system.
5. In Server Manager, go to Local Server, then Settings, and update Windows. Restart afterward.
6. In File Explorer navigate to DVD drive and install VMware Tools. Restart after installation has been completed.

## Post-Installation Tasks
- Take a snapshot of the VM in case there will be a need to roll back to the initial state of the system
- Update Windows Defender definitions (viruses and threat protection, app and browser control).

