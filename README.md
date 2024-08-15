# MyRio_I2C_Driver

LabVIEW FPGA Project - I2C Communication with Accelerometer and Magnetometer
This project demonstrates the development and implementation of an I2C communication system using LabVIEW FPGA, interfacing with an accelerometer and a magnetometer via a myRIO-1900. The primary focus is on reading sensor data, including accelerometer and magnetometer values, by managing the I2C communication protocol effectively.

Key Features:

I2C Communication Setup: Configured and initialized I2C communication between myRIO-1900 (Master) and external sensors (Accelerometer and Magnetometer as Slaves).
Reading Sensor Data: Developed sequences to read dummy registers and actual sensor data (X, Y, Z axes) from both the accelerometer and magnetometer.
Auto-incrementing Registers: Implemented auto-incrementing functionality to streamline reading of multi-byte data.
LabVIEW SubVIs: Created and utilized multiple SubVIs to handle specific tasks such as start conditions, address writing, data reading, and stop conditions, ensuring accurate data transmission.
Data Handling: Employed the "Join Number" function in LabVIEW to combine low and high bytes for accurate axis readings.
Front Panel Design: Designed intuitive front panels in LabVIEW for real-time monitoring and data acquisition from the sensors.
This repository includes the complete LabVIEW project files, including SubVIs, block diagrams, and front panel designs used to achieve the communication and data reading tasks.

