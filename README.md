NAME : N S V V JANAKI RAMA REDDY
COMPANY : CODTECH IT SOULTIONS
DOMAIN : EMBBED SYSTEM 
DURATION: AUG TO SEP 2024
INTERN ID: CTO8DS6104
MENTOR: Muzammil ahmed




OVERVIEW OF THE PROJECT 
Temperature and humidity monitoring using a DHT sensor is a popular choice for a variety of projects, especially in IoT (Internet of Things), home automation, and environmental monitoring applications. The most commonly used DHT sensors are the DHT11 and DHT22, which are simple, low-cost, and effective for measuring temperature and humidity.

COMPONENTS:
DHT Sensor: This is the primary component responsible for sensing both temperature and humidity. There are two versions typically used:

DHT11: Lower accuracy, slower sampling rate, but cheaper.

DHT22: Higher accuracy, wider range, faster response, but more expensive.

Microcontroller/Processor: Used to process the data from the DHT sensor. Examples include Arduino, Raspberry Pi, ESP8266, ESP32, etc.


WORKING PRICIPLE :
Temperature Sensing: The DHT sensor uses a thermistor (in DHT11) or a temperature-sensitive capacitor (in DHT22) to measure temperature. This element’s resistance or capacitance changes with temperature, which is then processed to give a digital output.

Humidity Sensing: The sensor measures relative humidity (RH) using a resistive or capacitive element. When the humidity level changes, it alters the electrical resistance or capacitance in the sensor, which is converted to a readable value.


INTERFRENCE:
Wiring: The sensor usually has 3 pins: VCC, Data, and Ground.
Connect the VCC to a 3.3V or 5V power supply, Data pin to a GPIO pin of the microcontroller, and Ground to the ground.
Libraries: Many platforms (Arduino, Raspberry Pi) provide libraries to easily interface with DHT sensors. For instance, in Arduino, you might use the DHT library.

APPLICATIONS:
Weather Stations: Measure temperature and humidity in real-time.
Greenhouses: Monitor environmental conditions to ensure plants' optimal growth.
Home Automation: Control HVAC systems based on temperature and humidity data.
Data Logging: Collect environmental data for analysis or predictive purposes.

ADVANTAGES:
Simple to use with readily available libraries and tutorials.
Low cost, making it ideal for hobbyist projects.
Compact design for easy integration into various devices.

LIMITATIONS:
Limited accuracy, particularly in DHT11.
Slow response time, especially in fast-changing environments.
Low sampling rate, not suitable for real-time critical applications.
