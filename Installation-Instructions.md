### Installation Instructions: ###


1. Download and install [Etcher](https://etcher.io) or [Win32 Disk Imager](https://sourceforge.net/projects/win32diskimager/)

2. Write the openipc_v0.2.4.img to your SDcard

3. Open the SDCard and edit the files .wifissid and .wifipasswd to match your network

4. Flash the firmware to the camera:


    - Hold down the setup button for 10 seconds BEFORE connecting power
    - With button still depressed, plug in power to the camera while continuing to hold for another 10 - 12 seconds.
    - Release the button when the connection light blinks continually.
    - Press the button again and you should hear a Chinese voice prompt if successful.


5. Remove SDcard and reboot camera and reinsert after boot until you hear "click click".

6. Repeat Step 5 until you hear "click click".

7. Run openipscan.sh or openipscanwin.sh if you're on windows/mac and find the IP address of your new OpenIP Camera. Note: MAC address will be changed to c0:6d:1a*

8. Proceed to the status web page and apply the hacks. http://[discoveredipaddress]/cgi-bin/status

NOTE: of you get a 404 error with a flashing blue led, Remove the sdcard and reinsert it. Shortly after thst the camera will go "click click" again. Proceed to the link now



Congratulations! Welcome to OpenIPC.