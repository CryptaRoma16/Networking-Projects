# How to Fully format my USB drives with D and E so on only using commands?
- For always try to format their USB but error occurred and can't format using the (right-click) then Format/quick format.. or in Disk management. (Isn't crazy) So this is the solution..

#### For Windows 11
Here's one of my example USB drive with D and E storage:

This is for super easy format your USB drive by using only few command.
Warning: it will erase all data on your USB drive

Now let's tart:

1. Make sure the USB drive is plug in to your computer.
2. Point your mouse in Start window > Right-click and Select the Terminal(Admin).
3. Type these commands: (see the image below for your reference)
   
-```diskpart```

-```list disk```

-```select disk 1``` (Ey! Careful make sure the disk number is for USB drive ok?)

-```clean```

-```create partition primary```

-```format fs=ntfs quick```

![commands](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img2/commands.png)

![formatntfs](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img2/formatntfs.png)

![DriveD](https://github.com/CryptaRoma16/Networking-Projects/blob/main/img2/driveD.png)

Well done! - Here you don't need to assign a letter, it will automatically assigned it.
