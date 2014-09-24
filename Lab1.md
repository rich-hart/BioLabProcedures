Lab1: 


##### Start Up Raspberrian Graphics User interface

log into raspberry pi 
	
Go to raspi-config
```sh
	sudo raspi-config
```

Boot To Desktop
	```sh
	Enable Boot To Desktop --> Desktop
	Finish
	```
	
Wait for restart


##### Start Arduino IED

Start Terminal in Rasparian GUI

	```sh
	Double click LXTerminal
```

Make sure arduino IED is installed

```
sudo apt-get install arduino
```

Install Java
```
sudo apt-get update && sudo apt-get install oracle-java7-jdk
```

Remove Wolfram
```
sudo apt-get autoremove wolfram-engine
```
Start running arduino IED
```
arduino
```

Notes:  I don't know if the flowing command was needed. 
```
startx arduino
``` 
Notes: Also Running it From the Gui Also Works 

Notes:  Program Takes a long Time to Start Up



##### Open Blink Example Scetch
Caution: It can be slow to start up

Plug in Arduino Uno (w/out danger shield)

Open Up Blink Example Scetch
```
Click on File->Examples->Basic->Blink 
```
Verify Setch

Upload and Compile

Select Proper port for arduino

Arduino LED Should blink

Discussion:  Overview of what just happened.
What is the most basic setch you can have? I think it needs a loop(){}


##### Using Arduino To Generate Simple Data
Subtitle: Write Data Serial. a.k.a sending information to raspberry pi

Create a blink Counter

Every time the blink counter is incremented 
write it to serial.



 

Discussion: What is serial?
##### Using RaspberryPi to Interpret Data From Arduino

Read Data From Serial and Print it to Comamnd Line Using Python Script


