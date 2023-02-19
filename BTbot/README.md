
# What is that?


A zumo-like robot controlled by means of a bluetooth link. Use this code to your own.

This needs a zumo-like robot and a couple of bluetooth modules. For this test project, HC-05 (master) and HC-06 (slave) modules have been used. It also needs the zumo-shield library to control the zumo motors, and the Softserial library to emulate a serial port in order to allow debuging option.

There are 3 variants to control the robot: 1) controlled by one joystick at full speed, 2) controlled by one joystick sensitive to movement (the larger joystick movement, the higher speed) and 3) controlled by two joystick sensitive to movement.

Demo videos can be found in media folder.


Published under GNU/GPL v3.0 or higher.



#### References

[Martyn Currey's tutorial](http://www.martyncurrey.com/arduino-to-arduino-by-bluetooth/)

[How to configure a pair of BT modules](http://howtomechatronics.com/tutorials/arduino/how-to-configure-pair-two-hc-05-bluetooth-module-master-slave-commands/)