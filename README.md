# Windows Server Active Directory Lab

## Objective

This Windows Server Active Directory Lab aimed to establish a simulated work environment using virtual machines and Active Directory. The primary focus was for me to develop familiarity with creating and managing users, groups, OUs, GPOs and file/foilder permissions. This hands-on experience was designed to introduce me to the basics of Active Directory.


### Skills Learned

- Creating and managing OUs, Users, and Groups in Active Directory to simulate a work environment
- Managing User Account access - resetting passwords, account lock/unlock, and setting active hours
- Joining a user machine to the domain using a static IP address
- Group Policy Management - Creating, managing, applying and testing GPOs and security across different groups and users
- File Sharing Services - Set up network shares and managed folder/file permissions 
- Utilized NTFS permissions and network shares to test access-based enumeration
- Implemented a simple service account

### Tools Used

- VirtualBox to set up the virtual work environment for the Server and user machines
- Windows Server 2022 and Active Directory to deploy changes for users and groups joined to the domain

## Steps

*Ref 1: Setting up DNS on Windows Server and user machine with static ip addresses*
<img width="1919" height="1079" alt="AD-Lab_DNS-Config" src="https://github.com/user-attachments/assets/aed2e42e-5eef-4ca4-a188-5364dd6c5e7b" />

*Ref 2: Joining the end user machine to the domain*
<img width="743" height="677" alt="AD-Lab_Join-Domain" src="https://github.com/user-attachments/assets/07bbd0ce-dbed-4a6e-8ddd-1da284c4b014" />

*Ref 3: OU setup with different OUs, users and groups as needed for each department in the region*
<img width="939" height="677" alt="AD-Lab_OU-Setup" src="https://github.com/user-attachments/assets/770520a3-3409-4e1a-ad8e-3a5ebb765a1c" />

*Ref 4: Here are some of the GPOs I created to help boost security, like account lockout and password policies, as well as policies that restrict the use of certain features, like control panel and USB devices.*
<img width="444" height="898" alt="AD-Lab_GPO-Policies" src="https://github.com/user-attachments/assets/1c0e01b7-acaa-4022-b10b-409f4010c5e1" />

*Ref 5: The Desktop Wallpaper GPO changed the wallpaper for all users to this funny image of Matikanetannhauser*
<img width="1460" height="977" alt="AD-Lab_Wallpaper" src="https://github.com/user-attachments/assets/81aef019-5b28-45db-8702-1520d9ab43bf" />

*Ref 6: In this screenshot, I set up network sharing on the user's machine but changed the NTFS permissions and enabled access-based enumeration making the confidential HR folder not visible to this user on the IT team*
<img width="1908" height="1011" alt="AD-Lab_Network-Share-Access-Based-Enumeration" src="https://github.com/user-attachments/assets/195747d2-eac8-40be-877b-3dfc107ed4ed" />


