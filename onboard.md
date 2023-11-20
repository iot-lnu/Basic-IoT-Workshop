### 1. Log on
Got to [The things network console](https://console.cloud.thethings.network/). Select Europe 1 (eu1) and choose the `Login with The Things ID` option to log in. Use the credentials provided by the instructor. Go to 'applications' and click on the one called 'Basic Workshop'.

![](https://i.imgur.com/3apo8Cv.png)

### 3. Add your sensor to the application

Once there, navigate to `Register end device` in the bottom-right corner to add your *Sensor* to the application. For some sensors the details are already added in TTN. Search for its brand name in the search bar under "End device brand". If the sensor is not in TTS's LoRaWAN device repository yet, you can still add it manually.

Set the **frequency plan** to `Europe 863-870 MHz (SF9 for RX2 - recommended)`, **LoRaWAN version** to `MAC V1.0.2` and the **regional parameters version** to `PHY V1.0.2 REV A`. 

Enter the `JoinEUI`, `DevEUI` and the `AppKey` that are provided and click `Register end device`. 

![Alt text](/images/i15.png)

Once you register your device, you will be directed to the device page, which should look similar to the image below. 

![Alt text](/images/i16.png)


And in The Things Network `Live data`, we can read the sensor values in the payload (as hex). In the example we can see 17 (23 in decimal), which is our temperature, followed by 30 (48 in decimal), which is our humidity. 

![Alt text](/images/i20.png)

If you made it this far, congratulations! 🥳 

You can now move on to visualizing the data! 