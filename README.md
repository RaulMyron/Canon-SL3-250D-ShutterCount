# Canon-SL3-250D-KissX10-ShutterCount

⚠️ ⚠️ ⚠️ FIRST OF ALL DO THIS BY YOUR ACCOUNT AND BUSINESS I AM NOT RESPONSIBLE FOR YOU BRICKING YOUR SYSTEM OR YOUR CAMERA, PLEASE BE AWARE ⚠️ ⚠️ ⚠️ 

# For the moment being my firmware was 1.0.3 :)

# This script helps my BROTHERS AND SISTERS that need to know the shutter count on the canon sl3 - WINDOWS ONLY

# All thx to [@Mechite](github.com/Mechite) and  [SHDK wiki Original Link](https://chdk.fandom.com/wiki/Canon_Basic/Card_Setup)

You can do this two ways, the easiest way you can do is:

## Way 1
1. Using the (EOScard Software)[https://web.archive.org/web/20170608030518fw_/http://pel.hu:80/down/EOScard.exe] just check the script and save it:
![image](https://github.com/RaulMyron/Canon-SL3-250D-ShutterCount/assets/39887348/abed0289-6e81-476c-b3ba-bddf16e4848a)
## Way 2
Editing your SDcard with a hex editor (suggested HxD and DO NOT SHIT THIS UP PLZ ⚠️ ⚠️ ⚠️)
1. In HxD: Tools -> Open Disk -> Choose Your SD Card (Please BE AWARE THAT U CAN BREAK YOUR DISK and uncheck for the SD card the "Open as readonly" box) -> Click Ok
2. There you gotta find the 1F0, so CTRL + G on it, then finding it substitute the points on right for SCRIPT.
![image](https://github.com/RaulMyron/Canon-SL3-250D-ShutterCount/assets/39887348/6a00f86c-a517-4685-ad8f-4d2f7c182971)

For any way taken, now we gotta continue.

What you're supossed to do NOW is (i'm gonna let the codes of it availabe in the rep folder):
1. Create a ```script.req``` file with the code:
```for DC_scriptdisk```
inside of it.
2. Create a ```extend.m``` file with the code:
```
private sub Initialize()
    CamInfo_Debug(1)
end sub
```
That is the canon basic script, after that it should all be done :).
Last: Put the SDcard inside of your cam, go to the gallery then click SET. it should generate. then voilá. it's ready. just read your .XML file with the shutter count. Open the SDcard on Windows Again.
![image](https://github.com/RaulMyron/Canon-SL3-250D-ShutterCount/assets/39887348/86247ede-46dc-4213-9386-481e4539561f)
The file generated
![image](https://github.com/RaulMyron/Canon-SL3-250D-ShutterCount/assets/39887348/1252ac0e-1b9d-4e68-8b43-564f35afacf3)
It should be in the tag <TotalShutter></TotalShutter>.

That's it today folks. Goodbye. My pc just broke if u wanna support me: raul.myron@gmail.com (pix and paypal) 








 
