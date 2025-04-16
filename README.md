Network Security Assignment-4
Report on Vera Crypt Tool
Shashwat Amrit/220905266/roll-37/CSE-A
 VeraCrypt
1.Information
VeraCrypt is an open-source disk encryption software that provides enhanced security for data protection. It is a successor to TrueCrypt and is widely used for encrypting entire storage devices, partitions, or creating secure virtual disk containers.
2.Features
•	Supports AES, Two fish, and Serpent encryption algorithms
•	On-the-fly encryption without performance loss
•	Hidden volume and hidden operating system for plausible deniability
•	Cross-platform support (Windows, Linux, macOS)
•	Pre-boot authentication for system drive encryption
3.Relevance
VeraCrypt is essential for individuals and organizations seeking secure data storage. It protects sensitive information from unauthorized access, making it valuable for cybersecurity professionals, privacy advocates, and businesses handling confidential data.
4.Configuration Steps
•	Create Encrypted Volume:
1.	Click Create Volume
2.	Choose Create an encrypted file container
3.	Set location and size
4.	Select encryption (AES is default)
5.	Set a strong password
6.	Format and mount the volume
•	Encrypt a Partition or Entire Drive:
1.	Choose Encrypt a non-system partition/drive
2.	Follow the wizard to select options and password
•	System Drive Encryption:
1.	Click System → Encrypt System Partition/Drive
2.	Complete wizard including rescue disk creation
5.Use Cases
1.	Secure USB Drive:
o	Encrypt USB to store sensitive files securely
2.	Personal Data Protection:
o	Create hidden volumes for storing confidential documents
3.	Pre-Boot Authentication:
o	Encrypt entire OS drive with password prompt before boot
4.	Cross-Platform Access:
o	Mount encrypted containers on Linux and macOS
6.Issues Encountered
•	Driver Errors on Windows: Fixed by running as administrator
•	Rescue Disk Requirement: Can't skip during system encryption



Website/referncehttps://www.veracrypt.fr 
 
 

 







