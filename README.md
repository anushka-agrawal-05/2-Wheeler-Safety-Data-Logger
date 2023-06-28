 ---
# 2 WHEELER SAFETY - Data Logger

## Project Overview
---

This IoT based 2 WHEELER SAFETY project focuses on imporving road safety for vehicles. The project involves data logging and analysis of angular velocity, acceleration, and GPS tracking of vehicles using sensors and Arduino. The collected data is analysis road conditions and take required measure to ensure road safety.

> For more details about the implementation please refer to the [Project Report](Report.pdf)

## File Structure
--- 

The repository contains the following directories:

1. `mpu`: This folder contains the code for the functioning of the MPU6050 sensor, which measures linear acceleration and angular velocity along all three planes (x, y, z).\
2. `mpu_sd`: The code in this folder is responsible for logging the values obtained from the MPU6050 sensor into the SD card.
3. `gps`: Here, you can find the code for retrieving values from a GPS module, including date, time, latitude, and longitude.
4. `final`: This directory integrates the GPS, MPU, and SD card functionality. The sensor and GPS values are stored in the SD card as a CSV format, which can be further utilized for data analysis.

## Instructions
---

1. Open the respective folders to access the code for specific functionalities.
2. Upload the code to the Arduino board using the Arduino IDE.
3. Connect the MPU6050 sensor and GPS module to the Arduino board as per the circuit connections specified in the code and report.
4. Run the final code from the "final" folder to enable data logging and analysis.

> Note: Please refer to the individual code files and the project documentation for more detailed instructions on usage and further development.
> Note: Make sure to install the necessary libraries and dependencies as specified in the code files.

## Requirements
---

The project requires the following components:

* Arduino board
* MPU6050 sensor
* GPS module
* SD card module
