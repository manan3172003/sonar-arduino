# sonar-arduino
An arduino project which uses the HC-05 and a servo motor to calculate the distance of an object from the sensor. The HC-05 sensor detects the ultrasonic soundwaves that are omitted by it and returned to it after colliding with the object. It uses the time taken for the soundwave to return back and the angle at which the object is located to calculate the distance between the sensor and the object

1) open the arduino_connection>arduino_connection.ino in the Arduino IDE
2) connect the hardware to your pc and select the port in which arduino is plugged
3) upload the code onto the arduino UNO chip
4) inside the visualiser>visualiser.pde, change the port name to whichever port the arduino is connected to
5) run the processing file
