# Weather Station & Temperature controlled AC

Project By:
- Muhammad Salman
- Muhammad Usman Zafar
- Syed Faseeh ul Hassan

--------⁕-------------------------------------- ⁕-------
### Problem Statement
An IOT and AI Project for Live and Future Weather Forecasting based on Machine Learning Techniques.
![image](https://github.com/user-attachments/assets/ef34f0d1-f5fa-4f98-b961-157c4aa55014)

### Tools And Material Used
- Hardware
- Arduino Uno
- DHT11 Temperature and Humidity Sensor
- BMP180 Pressure Sensor
- Rain Sensor
- Relay Module

### Other Tools
- Arduino IDE
- Python
- VS code
- Jupyter Notebook
- My SQL Server
- Xampp Control Panel
- phpMyAdmin

### Languages  and Libraries Used
- Python
- C++
- SQL
- Pyserial
- MySQL-Python

<img width="535" alt="image" src="https://github.com/user-attachments/assets/94b466c9-41a1-4fbd-a80d-1c8bb3232dd9">

### Data From Arduino

- Raining  1	|	Not raining  0 

- Temperature in Celsius(C)

- Humidity percentage(%)

- Pressure in HectoPascal(hPa)

<img width="249" alt="image" src="https://github.com/user-attachments/assets/82998bfd-9756-4640-8788-7e299b87586d">

### Data Analysis Techniques

- Artificial Neural Network(ANN)
- Random Forest Regression

### Artificial Neural Network(ANN)
- We have used ANN for rain prediction using three features: Pressure, Temperature, Humidity.

### Random Forest Regression
- We used  Random Forest Regression for temperature prediction using three feature date.

### Graph Against Minutes And Temperature Predicted

![image](https://github.com/user-attachments/assets/756a5d82-6e14-4954-9d45-683b42953406)

### Temperature Controlled AC
We are using temperature parameter to control Air cooler or AC. When temperature increases from specific range the AC turns ON and when it goes below specific range the AC turns OFF.
For this we used relay module which turns off and on the AC after getting signal from arduino.
