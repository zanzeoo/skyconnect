# skyconnect



Skyconnect is an electronic project that allow you to control  telescope mounts throught wifi , bluetooth or RS485. 
It also can be used to control the shutter of a DSLR camera

BOM : https://octopart.com/bom-tool/n0BOnnqq


Shutdown temporarely your home WIFI.
Disable 4G/5G data of your smartphone
Enable WIFI , you shoud see DoitWiFi_xxxx.
Open your Browser at 192.168.4.1 (it's the built in web server)
In serial menu :baud rate:9600, databits:8, parity: none, stopbits:1, serial split timeout : 200. Click save.
In network Menu :configure the module in UDPserver on port 11880. Save

In More menu , select Restart ,the module should restart , then reconnect to it . 

To use it with Syncscan pro with your smartphone, in Synscanpro menu, Try to use a timeout serial link between 200 and 400ms
Tu use is with stellarium , with your smartphone, start Synscanpro before then start stellarium

If you want to use it in bluetooth just replace to DT-06 WIFI module by a HC-06 BLUETOOTH module

If you want to use it with a RS485 link (the wire link could be more than 500 meters long) you have ti use a USB to RS485 adapter.
Use a 4 twisted paire cable and dont forget to solder GND both side (use the minus pin of the 12v header)
