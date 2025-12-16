# TASK 2 – Sensor-Based IoT Simulation

## Aim
To simulate an IoT-based system where an LED is automatically controlled using a temperature sensor.

## Software Used
- Tinkercad (Online Simulation Tool)
- Arduino UNO

## Components Used
- Arduino UNO
- TMP36 Temperature Sensor
- LED
- 220Ω Resistor
- Breadboard
- Connecting Wires

## Description
This project demonstrates a simple IoT sensor-based simulation.
The temperature sensor continuously measures the surrounding temperature.
Based on the temperature value, the LED is automatically turned ON or OFF.

## Working Principle
- The TMP36 temperature sensor gives analog output based on temperature.
- Arduino reads the sensor value using the analog pin.
- If the temperature exceeds 30°C, the LED turns ON.
- If the temperature is below 30°C, the LED remains OFF.

## Algorithm
1. Start the program.
2. Read temperature sensor value.
3. Convert sensor value into temperature.
4. If temperature > 30°C, turn ON the LED.
5. Else, turn OFF the LED.
6. Repeat the process.

## Code Explanation
- `analogRead()` reads the sensor data.
- Voltage is calculated from the sensor value.
- Temperature is derived from voltage.
- `digitalWrite()` controls the LED based on temperature condition.

## Output
- LED turns ON when temperature is high.
- LED turns OFF when temperature is low.
- Temperature values are displayed in the Serial Monitor.

## Result
The sensor-based IoT simulation was successfully implemented and verified using Tinkercad.

## Screenshots
Circuit diagram and serial monitor output screenshots are included in the `screenshots` folder.
