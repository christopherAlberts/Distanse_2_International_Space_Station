# Distanse_2_International_Space_Station

This code make's use of the IPSTACK API to get one's Latitude and Longitude via one's IP-address. In order to do this you'll need to acquire an IPSTACK TOKEN and past it into the code. You can get your IPSTACK TOKEN here:

*https://ipstack.com/*

## The way to run this code:

The main method is the iss() method. You can either import this method into your own code or you can uncomment the iss() method at the bottom of the code and merely run the iss.py file. The iss() method will only execute the code once. If you would like the code to run continuously and watch the International Space Station move you can execute the iss_loop() method. This can also be uncommented at the bottom of the iss.py file. 

*Once executed the code will display something like this... *

```
########################################
      International Space Station
########################################
----------------------------------------
	   You are currently 
	   >>> 10199.35km <<<
 from the International Space Station.
----------------------------------------
╔═══════════════╤══════════╤═══════════╗
║               │ Latitude │ Longitude ║
╠═══════════════╪══════════╪═══════════╣
║ Your location │ -34.2308 │ 22.0585   ║
║ ISS location  │ -2.9080  │ 58.9281   ║
╚═══════════════╧══════════╧═══════════╝

----------------------------------------
 The International Space Station will
 be passing over you 5 times today.
----------------------------------------
╔════════╤══════════╤═════════════════════╗
║ Number │ Duration │ Risetime            ║
╠════════╪══════════╪═════════════════════╣
║ 1      │ 3.95     │ 2019-08-10 20:36:02 ║
║ 2      │ 10.78    │ 2019-08-10 22:08:43 ║
║ 3      │ 8.47     │ 2019-08-10 23:46:50 ║
║ 4      │ 3.28     │ 2019-08-11 04:45:53 ║
║ 5      │ 10.23    │ 2019-08-11 06:20:04 ║
╚════════╧══════════╧═════════════════════╝

----------------------------------------
 There are currently 6 people in space.
----------------------------------------
╔════════╤═════════════════════╤═══════╗
║ Number │ Astronauts          │ Craft ║
╠════════╪═════════════════════╪═══════╣
║ 1      │ Alexey Ovchinin     │ ISS   ║
║ 2      │ Nick Hague          │ ISS   ║
║ 3      │ Christina Koch      │ ISS   ║
║ 4      │ Alexander Skvortsov │ ISS   ║
║ 5      │ Luca Parmitano      │ ISS   ║
║ 6      │ Andrew Morgan       │ ISS   ║
╚════════╧═════════════════════╧═══════╝

```




