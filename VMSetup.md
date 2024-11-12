# Instructions to Set Up Virtual Machine 

1. Open up Box and look for the 101 Hardening Lab Folder

[Box Link](https://byu.box.com/s/glivxjlh23kkpwogxkg7a5r6uahm6mx1)

3. Look for the Windows 10.iso file and copy it over to your Downloads folder 

4. Open VMware Workstation pro (should already be on the computers)
 
5. Click 'Create new virtual machine' and select 'typical'

6. For the installer disk image, have them browse to and select the ISO in Downloads folder. **NOT THE ONE IN THE SHARED FOLDER**

![image](https://github.com/user-attachments/assets/401515bc-5dc1-46b8-b016-c9a488b4bd32)


6. Click Next and keep defaults for Virtual Machine Name
   
7. When specifying the disk size in the next step, be sure to set it to **20 GB**. The default is 60, which is way more than needs to be taken up on the lab computers.

8. Choose to store the virtual disk as a single file

![image](https://github.com/user-attachments/assets/b00eedb4-e655-473c-93c3-b8d1424431f0)

9. Click Finish

10. Here's the tricky part:
When the machine is first booting up, there will be a screen that appears for a few seconds that says to press any key to proceed with boot, or something like that.... If you don't press a key during those few seconds, the boot will fail, and you will need to manually restart the machine from within VMware and try it again. Some people might notice that even if they hit a key, nothing will happen and its most likely because they need to click on the VM window with their pointer to actually tell VMware to have the VM accept keystrokes.

11. To regain control of your mouse, you need to hit CTRL + Alt

![image](https://github.com/user-attachments/assets/c736b26c-0a0d-4440-81f6-b2289e1f5c38)

12. Click I don't have a product key

![image](https://github.com/user-attachments/assets/790caefb-2d02-4c53-97a1-f02855e4c45d)

13. Choose **Windows 10 Pro** for the Operating System you want to install

14. Choose Install Windows Only (bottom choice) and choose Drive 0 unallocated Space

![image](https://github.com/user-attachments/assets/ffb6ae5e-6996-453b-87e4-320ee25286ac)


15. Now, after waiting for Windows to install, you should be setting Windows up. Just click the defaults and set up a personal account. 

16. On this screen, select Offline account and then Limited Experience on the next screen. This makes it so you do not need to login with a Microsoft account.

![image](https://github.com/user-attachments/assets/94f00ebf-c8a3-43f0-b20a-e49db1ac3dc1)

17. On these next screens, create a memorable username and password. You will use them.

![image](https://github.com/user-attachments/assets/fed27311-d316-4b9b-987f-062442d2ba35)

18. Get through the security questions and the personalized expereince screens and Windows will be almost done setting up!

![image](https://github.com/user-attachments/assets/c3016909-4328-4f6e-9d42-a82bf5dee9a8)

![image](https://github.com/user-attachments/assets/0aa81b40-027e-45ce-b1ed-cbc7f51f8f13)

CONGRATS!! Now you can start the lab!!!

Head over to [HardeningLab.md](https://github.com/Skid1254/101-OS-Hardening-Lab/blob/main/HardeningLab.md) for lab instructions.

