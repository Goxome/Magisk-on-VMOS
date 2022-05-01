# Magisk on VMOS

Magisk successfully installed on VMOS - but Magisk can't work properly

<img src="https://user-images.githubusercontent.com/56850970/166162388-30fc4916-275d-4d6c-bd00-b8db3d0806c7.png" />


Hi guy, finally I installed Magisk on VMOS successfully!! Magisk daemon can be running but it can't work properly maybe due to VM limitations.

The newer Magisk app can't detect installed Magisk. 

<img src="https://user-images.githubusercontent.com/56850970/166162473-246f742e-477d-43f7-97d8-883e0537a34a.jpeg" />

But I can grant MagiskSU (make a Superuser request)... Only MagiskSu works

Video: https://youtu.be/x

Remember: All "Magisk on VMOS" videos uploaded to YouTube are fake.  They just install the Magisk manager app (like any app you install with "file.apk") on the VMOS.

NEW!! Magisk Manager v.8.0.0 can detect installed Magisk.

<img src="" />



<img src="https://user-images.githubusercontent.com/56850970/166162475-97cfcc3f-0709-4edf-b29a-32eca2adc967.png" />

I have made a script to install Magisk as VMOS Tool Terminal modification on VMOS. NOTE that Magisk on VMOS cannot work properly and it is for TEST only!!!

Magisk mount folder: `/sbin/magiskimg`

### How to install Magisk for VMOS Pro

This is unstable build, so it cannot work properly at all!!

File: [magisk.zip](https://github.com/Goxome/Magisk-on-VMOS/releases)

Video: https://youtu.be/x

1. Install VMOS Pro Terminal Tool v1.8+ if it's not installed! Or you can download my Geek ROM with Terminal Tool installed.

2. Download `magisk.zip` and import file to VMOS Pro

3. Extract `magisk.zip` to `magisk` folder

4. Copy `magisk` folder to `/sdcard/toolflash/`

5. Open Terminal app, type `su` (grant root access) then type `tool` to run VMOS Pro Terminal Tool, then type `6` (Enter) and `yes` (Enter) to install module.

<img src="https://user-images.githubusercontent.com/56850970/166162732-5e049592-6b99-4f81-ab16-f129bf924d8e.jpg" />




6. Reboot the virtual machine.

If you want to remove Magisk or switch back to Koush Superuser, just uninstall and reinstall root!!!


