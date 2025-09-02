# MQTTMotionSensor
A microcontroller Raspberry Pi Pico 2W with a gesture sensor PAJ7620U2 switches light by sending MQTT commands to the central home management system FHEM. The current status is shown by an LED.
The status shall be:
1. Gesture UP - Light is switched on and stays on (green)
2. Gesture LEFT or RIGHT - Light follows the motion sensor (yellow)
3. Gesture DOWN - Light is off and stays off (red)
