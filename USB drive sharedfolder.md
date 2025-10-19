## How to share a folder from USB drive to another PC thru network
#### For Windows 11

Before you share your folder you need to make sure they are same Domain name (Example: The default name is WORKGROUP)

To check if you are in the same domain name:
1. Press the ```Windows Key + I``` at the same time to open the settings app.
2. From the Settings app, click on the "System" category in the left-hand menu.
3. Scroll down to the bottom of the System menu and click on "About"
4. For my example, I only want to share 1 folder inside my USB drive. You need to create a folder and rename it to ```"SharedFile"``` - you can rename it on your own.

 ![inside USBdrive](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/inside%20USBdrive.png)

5. Once you created the "SharedFile" folder, right-click go to ```Properties > Sharing > Advanced Sharing > Check the "Share this folder".```
   
 ![sharing](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/sharing.png)
 ![checkshare](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/checkshare.png)

6. Then click Permission button > In permissions for everyone > Check all Allow boxes ```(Full control, Change, Read)``` then click Apply.
 
  ![permission](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/permission.png)

7. Next, go to ```Control Panel > Network and Internet > Network and Sharing Center > Click the "Change advanced sharing settings" >:```
 
 ![settings](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/settings.png)

8. So, go to ```password protected sharing > Turn off password protected sharing.```
Note: This settings is to prevent asking you the username and password every time you access the folder.
9. Now that it is shared, let's check to our network, if you have another laptop or PC you can access it by
   Pressing ```Windows key + R``` and type ```\\192.168.X.X``` the IPv4 address from PC with that USB drive.
   To check IPv4 address from PC with USB drive, press ```Windows key + R``` and type```cmd ```and type ```ipconfig```

 ![typeIP](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/typeIP.png)

10. Now you can see the "SharedFile" folder.
 
 ![sharedfile](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img/sharedfile.png)

Tips: You can also share the USBDrive itself from the network to see the all files inside.

