# CODETECH-task2
Full name : BEVARA RAJARAMESH
company:CODETECH IT SOLUTION
ID:CT08DS2073
Domain name : EMBEDDED SYSTEMS
mentor:G. SERVANI
[7:24 PM, 7/10/2024]
Raja Ramesh: Interface a DHT sensor with an Arduino to measure
temperature and humidity. Display the readings on an LCD
screen or serial monitor summary 

To interface a DHT sensor with an Arduino to measure temperature and humidity and display the readings on an LCD screen or serial monitor, follow these steps:

Components Needed:
Arduino board (e.g., Uno, Nano)
DHT sensor (DHT11 or DHT22)
LCD screen (optional) with I2C interface or without I2C
Jumper wires
Breadboard (optional)
Steps:
Connect the DHT Sensor:

VCC to 5V on the Arduino
GND to GND on the Arduino
Data to a digital pin on the Arduino (e.g., D2)
Install Libraries:

Open Arduino IDE.
Install "DHT sensor library" by Adafruit.
If using an LCD, install "LiquidCrystal_I2C" (for I2C) or "LiquidCrystal" (for parallel connection).
Connect the LCD Screen (Optional):

For I2C LCD:
VCC to 5V, GND to GND, SDA to A4, SCL to A5.
For Parallel LCD:
Connect LCD pins to corresponding Arduino pins.
[7:24 PM, 7/10/2024] Raja Ramesh: Upload the Code:

Connect the Arduino to your computer.
Select the correct board and port in Arduino IDE.
Upload the code.
This setup reads temperature and humidity from the DHT sensor every 2 seconds and displays the readings on either the serial monitor or an LCD screen. Adjust pin numbers and addresses as needed.
