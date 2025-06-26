Steps to creating bootable USB using the command Line interface
---
1. Insert your USB to your computer.
2. Open command prompt with admin privildges.

    ![image](https://supportkb.dell.com/img/ka0Do000000E8XtIAK/ka0Do000000E8XtIAK_en_US_1.jpeg)

4. Enter to the DiskPart utility.

![image](https://github.com/user-attachments/assets/c181a9c5-49b9-412b-8642-7ab30d671a69)

5. List all drives connected to your computer.
6. Select your USB drive.
7. CLEAN - This wipes the drive.
8. CREATE PARTITION PRIMARY - Creates a partition.
9. ACTIVE - Marks the current partition as active.

![image](https://github.com/user-attachments/assets/6510a8ad-1c05-4632-b681-ae9d9b22b894)

10. FORMAT FS=NTFS QUICK - This formats the partition.
11. ASSIGN - Assigns a drive letter.
12. EXIT
13. Close you console window and copy all files from ISO image to the USB

[Dell Support](https://www.dell.com/support/kbdoc/en-ca/000136959/create-a-bootable-usb-flash-drive-using-the-diskpart-utility)

[Spiceworks Inc](https://community.spiceworks.com/t/how-to-create-bootable-usb-in-a-quick-way/1011098)
