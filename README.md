# WikiRobot
A robot which is wiki!

I'm learning and building a robot. A robot which needs to be very fast, and I like it to see it as a robotic course for myself.
This first version is built within these modules:

- Raspberry Pi 3 (Master Controller)
	- Mojo v3 FPGA module (Connecting Pi to motors and sensors)
		- MPU9250 INS sensor
		- NodeMcu (reading some sensors and sending data to Mojo)
			- SRF02 ultrasonic range finder