# IoT-monitioring-system-for-Aquaponics

![image](https://github.com/jasonngai01/IoT-monitioring-system-for-Aquaponics/blob/main/pic/total_setup.jfif)

This project aims to develop a Iot system by Microbit and MuseLab Wifi Booster to monitoring the Aquaponics Habitat in order to increase the accuracy and efficiently in experiment control.

![image](https://github.com/jasonngai01/IoT-monitioring-system-for-Aquaponics/blob/main/pic/block_program.png)

In this project, Microbit ,MuseLab Wifi Booster and Two liquid Sensor are used to tracking the Environment, Algae and Fish tank temperture change. 

![image](https://github.com/jasonngai01/IoT-monitioring-system-for-Aquaponics/blob/main/pic/sensor_algae.jfif)
![image](https://github.com/jasonngai01/IoT-monitioring-system-for-Aquaponics/blob/main/pic/sensor_fish.jfif)

ThingSpeak by Maths work are used to visualise the tank temperture change by time. 

3 Sensor data are sent out.

The Website of the Channel is below:
https://thingspeak.com/channels/1372469

![image](https://github.com/jasonngai01/IoT-monitioring-system-for-Aquaponics/blob/main/pic/thingspeak.jfif)


# Usage of scripts
1. Go to the https://makecode.microbit.org/#editor
2. Add the MuseLab extension
3. Paste the code from main.py to the editor (change your own wifi ssid and Password & and ThingSpeak code)
4. Export the .hex file
5. Connect the Micro:bit (without the wifi booster) to the computer and the drag the .hex file to the Micro:bit
6. Connect the Micro:bit to the wifi booster
7. Switch on the wifi booster
8. Go to the https://thingspeak.com to monitor the Aquaponics habitat