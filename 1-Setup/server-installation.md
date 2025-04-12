# Windows Server 2022 Installation

## Prerequisites

* VMware Workstation 17 Pro
  
  ![Information-about-VMware-Workstation](https://github.com/user-attachments/assets/19b7892e-9fa6-43d1-9661-1719641e4844)
* Windows Server 2022 ISO file
* Allocated system resources: 4 CPU cores, 6GB RAM, 80GB disk space, Network adapter - NAT.
  ![System-Resources-of-Windows-Server](https://github.com/user-attachments/assets/1311a552-ba72-46f4-8d4a-d1a6b206e36a)

## Steps:

1. Create a Virtual Machine with configured system resources.
2. Install Windows Server from an attached ISO file.
3. Configure network settings: 
    
    - Set up static IP to IPv4: 172.16.0.10
    - Subnet mask: 255.255.255.0
    - Preferred DNS: 127.0.0.1 (optionally, it may be set to 172.16.0.10)
    - For the purpose of this lab, the default gateway is left blank
    - After installation, the type of network communication should be changed to "Host-only".

4. Rename computer, e.g Server2022-DC1, and restart the system.
5. In Server Manager, go to Local Server, then Settings, and update Windows. Restart afterward.
6. In File Explorer, navigate to the DVD drive and install VMware Tools. Restart after installation has been completed.

## Post-Installation Tasks
- Take a snapshot of the VM in case there will be a need to roll back to the initial state of the system;
  ![Fresh-Installation-of-WinServer Snapshot](https://github.com/user-attachments/assets/fb73b1cc-e16b-44aa-98aa-b683f07016db)
- Update Windows Defender definitions (viruses and threat protection, app and browser control).
  

