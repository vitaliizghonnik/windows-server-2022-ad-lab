# Windows 10 Pro Client Setup with Administrative privilege

## Prerequisites

- VMware Workstation 17
- Windows 10 ISO file
- The domain controller is configured correctly
- Allocated system resources: 4 CPU cores, 6 GB RAM, 70 GB disk space, Network adapter - NAT.
  > Configure all virtual machines to use the same NAT network, ensuring they are on the same subnet and can communicate with each other seamlessly.
  
  ![image](https://github.com/user-attachments/assets/2bce89a8-c964-4760-b749-bcc69a08779e)
  
## Steps of configuration:

1. Rename the Windows PC in System > About  
2. Install the Remote Server Administration Tools for Windows 10 to access Active Directory and other administration tools, including AD Certificate Services Tools, AD DHCP Tools, DNS Tools, Group Policy Management Tools, Remote Desktop Services Tools, and Server Manager.
   The installation of *optional features* has been migrated to Settings > System > Optional Features.
   
   ![image](https://github.com/user-attachments/assets/dcd4d4e8-c272-46ce-8e01-add3af53effe)
3. Install additional software:
   
   - __Web browser__: Google Chrome.
   - __Remote desktop and remote support applications__: TeamViewer, AnyDesk.


# Windows 11 Enterprise Client Setup  

## Prerequisites

- VMware Workstation 17
- Windows 11 ISO file.
- The domain controller is configured correctly
- Set up a TPM password, as installing Windows 11 requires TPM to be enabled and configured.
- Allocated system resources: 6 CPU cores, 7.0 GB RAM, 80 GB disk space, Network adapter - NAT.
  ![Resources for Windows 11 Enterprise](https://github.com/user-attachments/assets/0d53951d-cd73-4d2d-8da6-001594f2bd3a)

## Steps of configuration:

1. Rename the Windows PC in System > About.
