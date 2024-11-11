# Instructions to Set Up Virtual Machine 

1. Open up file explorer and click on the search bar at the top of the window
  
2. Type in '\\DEFENSE-01\ISOshare' (you should see the folder pop up before you enter the whole name in)

3. Hit enter, and you should be able to see the folder with the ISO file in it

4. Select the file and hit copy, paste it into their local users folder

5. Open VMware Workstation pro (should already be on the computers)
 
6. Click 'Create new virtual machine' and select 'typical'

7. For the installer disk image, have them browse to and select the ISO in their local user directory. NOT THE ONE IN THE SHARED FOLDER

8. The next step can be left as default

9. When specifying the disk size in the next step, be sure to set it to **20 GB**. The default is 60, which is way more than needs to be taken up on the lab computers.

10. Choose to store the virtual disk as a single file

11. The last step can be left as default

12. Here's the tricky part:
When the machine is first booting up, there will be a screen that appears for a few seconds that says to press any key to proceed with boot, or something like that.... If you don't press a key during those few seconds, the boot will fail, and you will need to manually restart the machine from within VMware and try it again. Some people might notice that even if they hit a key, nothing will happen and its most likely because they need to click on the VM window with their pointer to actually tell VMware to have the VM accept keystrokes.
