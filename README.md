# Computer Science & Electrical Engineering Senior Design: 
## Smart Irrigation Network
### Texas A&M University - Texarkana
The files here are the versions used in class to demonstration a web application and GUI that can be used to control and automate a sprinkler system. 
---
The web application (see *app.py* and the *main.html* files) was built and deployed on a Raspberry Pi 3 in Python using the microframework, Flask. This device was also in charge of controlling multiple water lines using a relay board mounted on to the GPIO pins. The pin numbers used in the Python dictionary are based on the relay board we used, and would be subject to change.  
*sense.py* is a seperate script deployed on another Raspberry Pi to measure, store, and report multiple sensor readings from outside back to the application and the database on the hosting device.
The MySQLdb and Adafruit Python libraries were required for the database and some of the sensors.
The application also includes the commented out code needed for SMTP notifications to text or email.
Confidential information has been subbed with placeholders.
