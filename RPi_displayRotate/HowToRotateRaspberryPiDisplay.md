# How to rotate the Raspberry Pi Display

## Step 1 Edit Config.txt

start by editing the config.txt file:

```bash
udo nano /boot/config.tx
```



 Add one of the following lines to the bottom of the file:

```bash
display_rotate=0	//normal configuration.
display_rotate=1	//rotate 90 degrees.
display_rotate=2 	//rotate 180 degrees.
display_rotate=3	//rotate 270 degrees.
```

If you are using the Official Raspberry Pi touch screen you can use "lcd_rotate" rather than "display_rotate".



## Step 2 Save the Config.txt file

Save the file by using CTRL+'x', 'y' then ENTER



## Step 3 Reboot

 Then reboot using

```bash
sudo reboot
```

When the Pi restart the display should be rotated.

