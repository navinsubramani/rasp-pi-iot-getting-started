![alt text](https://github.com/navinsubramani/rasp-pi-iot-getting-started/blob/master/documentation/IOT%20Architecture.jpg)

# Notes to setup pi from scratch

Raw Notes to setup pi headless: https://github.com/navinsubramani/rasp-pi-iot-libraries/wiki/Bringing-up-Raspberry-pi-headless

# Sensor setup procedure with pi

Sunkee ds18b20 : https://github.com/navinsubramani/rasp-pi-iot-libraries/wiki/Sunkee-ds18b20-temperature-sensor-with-raspberry-pi

S8050 transistor: https://www.instructables.com/id/How-to-Control-Fan-on-Raspberry-Pi-4-With-Transist/

LED: https://thepihut.com/blogs/raspberry-pi-tutorials/27968772-turning-on-an-led-with-your-raspberry-pis-gpio-pins

# Python using Raspberry pi simulator

https://create.withcode.uk/python/A3

https://pypi.org/project/GPIOSimulator/

https://roderickvella.wordpress.com/2016/06/28/raspberry-pi-gpio-emulator/

# Python on pi documentation: 

https://www.ics.com/blog/control-raspberry-pi-gpio-pins-python
- RPi.GPIO module library is based on the inputs and outputs of GPIO  : https://sourceforge.net/p/raspberry-gpio-python/wiki/Examples/
- GPIOZero module library is oriented on the devices and sensor type : https://gpiozero.readthedocs.io/en/stable/

https://www.raspberrypi.org/documentation/usage/gpio/python/README.md

# IOT Server setup

No-IP for static IP: https://www.noip.com/

Setting up a server machine using NO-IP in a home network: https://www.noip.com/support/knowledgebase/using-no-ip-with-a-cabledsl-router/

# IOT Application protocol client-server

Communication protocol can be wifi, bluetooth, internet,... but there will have to be a application protocol that is used on top of them to communication application specific messages

MQTT : http://mqtt.org/

MQTT debugger: http://www.mqttfx.org/

Several MQTT brokers to test communication are on the Internet. One of the most popular is mosquitto. To test the communication, you can publish topics to test.mosquitto.org. The mosquitto broker is open source and can also be used in-house for sandbox testing or production use of MQTT communication.

MQTT LabVIEW library: 
- https://forums.ni.com/t5/Example-Program-Drafts/MQTT-Client-API-in-native-LabVIEW/ta-p/3520582?profile.language=en
- https://github.com/DAQIO/LVMQTT
- https://forums.ni.com/t5/Community-Documents/MQTT-Driver-for-LabVIEW/ta-p/3561289?profile.language=en
- https://github.com/Indie-Energy/AWS-IoT-RESTful/tree/master/Examples

MQTT Python library:
- https://www.digikey.com/en/maker/blogs/2019/how-to-use-mqtt-with-the-raspberry-pi
- https://www.abelectronics.co.uk/kb/article/1085/io-pi-tutorial---mqtt-control

# Reference materials

Documentation on GPIO pins: https://www.raspberrypi.org/documentation/usage/gpio/
