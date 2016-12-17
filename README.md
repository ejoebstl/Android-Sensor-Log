# Android Sensor Logger 

Very simple Android sensor data logger. I use it to generate test data for designing filters. 

* Connects to sensors of an Android phone: Accellerometer, Gyroscope, Uncalibrated Gyroscope, Magnetometer, Uncalibrated Magnetometer, Rotation Vector.
* Fetches sensor data as fast as possible.
* Writes the data into a CSV file, including a timestamp and the sensor type. 
* Goes well with matlab's `readtable` command. 

