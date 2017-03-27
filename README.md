## SainSmart IOT Series ##
###NO.1 DIY WiFi Lights with Blynk ###
- ****Hardware****
  
 `NodeMcu  or other esp8266 module`    　　`X1`

 `SainSmart 2-channel relay`       　　　　　`X1`
 
 `DC 5V Charger`    　　　　　　　　　　　`X1` 

 `220V Lamp`        　　　　　　　　　　　　　`X1`

 `USB cable`      　　　　　　　　　　　　　`X1`

- **Software**

  Arduino IDE

  Blynk for ios&Android

- **Step 1**

Install Arduino IDE 1.6.6 or other version [Download Here](https://www.arduino.cc/en/Main/OldSoftwareReleases#previous)

Install esp8266 lib for your Arduino IDE
click **file** → **Preferences** and add the following website in **Additional Boards Manager URLs**：

![1.jpg](http://on8x3o9y2.bkt.clouddn.com/1.jpg)
 
*http://arduino.esp8266.com/stable/package_esp8266com_index.json*

click **Tools** → **Board** → **Board manager**

![2.jpg](http://on8x3o9y2.bkt.clouddn.com/4.jpg)

Search **esp8266** in the Board mannager then  click **install**

![3.jpg](http://on8x3o9y2.bkt.clouddn.com/3.jpg)

After installation  you will find esp8266 or Nodemcu 0.9 etc in **Tools**

![4.jpg](http://on8x3o9y2.bkt.clouddn.com/4.jpg)

- ****Step 2****

Install Blynk   lib for your Arduino IDE

Download Blynk lib from GitHub [Download Here](https://github.com/blynkkk/blynk-library/releases/tag/v0.4.6)

Release the file and add to your Arduino IDE ***libraries***

Click *file* → *Examples* →*Blynk*

![5.jpg](http://on8x3o9y2.bkt.clouddn.com/5.jpg)

Download Blynk APP for your mobilephone
[www.Blynk.cc](www.Blynk.cc)

- **Step 3**

***Hardware Connection***

**`Nodemcu`**　　　　**`SainSmart 2-CH Relay`**

`VIN`　　　　　　`VCC`

`GND`　　　　　　`GND`

`D00`　　　　　　`INT1`

![6.jpg](http://on8x3o9y2.bkt.clouddn.com/QQ%E6%88%AA%E5%9B%BE20170321112845.jpg)
buy SainSmart relay [here](https://www.sainsmart.com/relay-1/relays/sainsmart-2-channel-5v-relay-module-for-arduino-raspberry-pi.html)

buy SainSmart esp8266 module [here](https://www.sainsmart.com/nodemcu-lua-esp8266-ch340g-wifi-internet-development-board-module.html)

- **Step 4**

 Please be sure to select the right ESP8266 module

 in the **Tools** -> **Board**
 
 Change `WiFi ssid`, `pass`, and Blynk `auth token` to run !

 Upload your code by Arduino IDE

 ![7.jpg](http://on8x3o9y2.bkt.clouddn.com/6.jpg)

Creat a new project in your own Blynk and you will get  `auth token`

![8.png](http://on8x3o9y2.bkt.clouddn.com/IMG_0088.PNG)

copy it and paste to Arduino ide code.

Make sure the **DEVICE** is Nodemcu or Esp8266!

![9.png](http://on8x3o9y2.bkt.clouddn.com/IMG_0089.PNG)

you can design your own IOT app,for example :we choose a **`Button`** to control our lamp
 
![10.png](http://on8x3o9y2.bkt.clouddn.com/IMG_0090.PNG)

Set the BUTTON connecting  **`D0`** PIN of Nodemcu

Click **►** to  get your device online！

Then you can control your lamp anywhere ！

Enjoy it! 

　　　　　　　　　　　　　　　　　　　　　　　　　Product by **[SainSmart.com](WWW.SainSmart.com)**