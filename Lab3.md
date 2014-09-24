Open Arduino and Midori ide via LXTerminal

Search for dangershield on sparkfun electronics webpage.

Go to github link.

Go to Firmware->Dangershield.ino

Copy and paist ino code into a new arduino sketch.  (ctrl-a is select all)

Attach danger shield to arduino, 

try verifying code (warning should come up about missing capacitance library)

Find Capacitive Sensor libary on Arduinos website CapacitiveSensor04.zip and download

NOTE: Sudo apt-get upgrade tajes a LONG TIME. 

NOTE: Arduino might be best if they could do it on their own laptops. 

Note: This next step only works on Arduino 1.0.5 , Trying to upgrade arduino using apt-get upgrade cause arduino to freeze)

Note: Recommend uploading everyones sketch on your own computer using arduino 1.0.5 and capactiance library. 

TIP: Bottom right of Arduino IDE will tell current port arduino is on. 

Go to arduino IDE and import downloaded zip file. 


Write data to file using script python Read_From_Serial.py > ArduinoOutput.txt.

Recommend Killing process entirely to stop it, you can disconnect danger sheild but serial port will change designation. 

Explain to them the range of sensors and actuators they can now use. 

*** maybe a good library to use would be email updates? ***

Next Lab, Python, how to use it, how to use it to parse txt file data and save it in a formate that can easily be read by databases.

This can be read by excel and can be loaded into sql databases. 

Ideally would do something like a single gas sensor first. 
