# Smart-Switch
## 110V SPDT controled by Google Asistant and Adafruit io   
*******************************************************************************************************************************
## all you need:

### **1. arduino esp8266 NodeMCU**    [Amazon link](https://www.amazon.com/dp/B081CSJV2V/ref=sr_1_1_sspa?dchild=1&keywords=nodemcu+esp8266&qid=1611385205&sr=8-1-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUExVUo1VFg0UDBEVjMyJmVuY3J5cHRlZElkPUEwMzIwODI2MlZaTEVNRzJBUDBFNCZlbmNyeXB0ZWRBZElkPUEwNTYyNjkzMU5WTEI1SjdJUTlDJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)

### **2. 5V Relay module**            [Amazon link](https://www.amazon.com/dp/B00LW2VLS0/ref=sr_1_7_sspa?dchild=1&keywords=5V+Relay+module&qid=1611385244&sr=8-7-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEzM04xTks5Q1dVSDBYJmVuY3J5cHRlZElkPUEwMzMwMzY0MjQzQk9BNzlaU0ZTSiZlbmNyeXB0ZWRBZElkPUEwMTQ2NDIzUU43NzFNRkg5NEZEJndpZGdldE5hbWU9c3BfbXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==)

### **3. 2.0mm solid conductors**     [Amazon link](https://www.amazon.com/-/zh_TW/dp/B07TX6BX47/ref=sr_1_2?dchild=1&keywords=wire&qid=1611385297&sr=8-2 )

### **4. 0.5mm solid conductors**     [Purchace link](https://cbcable.en.made-in-china.com/product/KFNJWiAUbQck/China-600V-Avss-0-5mm-PVC-Coated-Electrical-Wire-Cable.html )
*******************************************************************************************************************************
## Adafruit

### 1.get an Adafruit account
[Adafruit.com](https://accounts.adafruit.com/users/sign_up)

### 2.go to "io" => "+New Dashboard" and create a new dashboard

### 3.click on the dashboard you just create

### 4.click on the gear icon and go to "Create New Block" => "Toggle" and create a new feed(the feed name should be the same with 'Realay1' in the arduino code aka main.ino!!!!)

### 5.go to "key" and copy your IO_USERNAME & IO_KEY  


*******************************************************************************************************************************
## get an IFTTT account

*******************************************************************************************************************************
## arduino IDE code

### 1.download link
[Download Arduino IDE](https://www.arduino.cc/en/software)

### 2.setup usb port for arduino esp8266
#### go to "tools" => "port" => "COM6"(plug in your arduino through a micro usb port and you will see the update for the ports)

### 3.open main.ino and compile the code
#### if its getting error,try to download these library downbellow
[ESP8266WiFi.h](https://github.com/esp8266/Arduino/blob/master/libraries/ESP8266WiFi/src/ESP8266WiFi.h)
[Adafruit_MQTT.h](https://github.com/adafruit/Adafruit_MQTT_Library/blob/master/Adafruit_MQTT.h)
[Adafruit_MQTT_Client.h](https://github.com/adafruit/Adafruit_MQTT_Library/blob/master/Adafruit_MQTT_Client.h)

### 4.paste all the information downbellow
#### Your Wifi SSID
#### Your Wifi password
#### IO_USERNAME
#### IO_KEY
