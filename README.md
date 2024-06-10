# Real-Time Transformer Condition Observation System

## Project Overview

The Real-Time Transformer Condition Observation System is a comprehensive solution developed to monitor and control the health of electrical transformers using IoT technologies. This project, successfully completed by our team and published in a research paper, addresses the critical need for continuous transformer monitoring to prevent failures and ensure efficient power distribution.

## Research Paper

**Title:** Real-Time Transformer Condition Observing System  
**Authors:** Swati Aswale, Sumit Ingale, Namami Hire, Rushikesh Bharade  
**Affiliation:** Department of Electronics and Telecommunication, D Y Patil College of Engineering, Akurdi, Pune, Maharashtra

## Abstract

In modern electricity supply systems, transformers play a crucial role in transmission and distribution. Overloading due to high power demand affects transformer efficiency and reliability. Traditional monitoring systems lack continuous observation, leading to potential failures. Our IoT-based monitoring system measures transformer parameters such as voltage, current, temperature, and humidity using sensors. Critical changes trigger alerts sent to an Adafruit IO web server via Raspberry Pi Pico W, programmed to detect abnormal conditions. This system enables early issue detection, preventing serious failures, and provides significant cost savings by improving reliability and accuracy over traditional methods.

## Introduction

Transformers are vital for electrical power systems, and monitoring their condition is essential to prevent failures. Traditional systems require manual inspection, which is labor-intensive and prone to inaccuracies. Our project aims to automate transformer monitoring using sensor networks to collect and analyze data, improving efficiency and reliability. Parameters such as temperature, current, voltage, and oil level are monitored, and critical values trigger alerts to prevent failures.

## System Overview

### Block Diagram


### Components
  Sensors:Current, Voltage, Oil Level, Temperature, and Humidity sensors
  Microcontroller: Raspberry Pi Pico W
  IoT Platform:Adafruit IO

### Functionality

1. Data Collection:Sensors monitor transformer parameters continuously.
2. Data Processing: Raspberry Pi Pico W processes sensor data in real-time.
3. Alert System: If any parameter exceeds threshold limits, the system sends alerts to Adafruit IO.
4. Control Mechanism: The system can turn on/off the transformer to prevent damage.
5. Real-Time Display: Data is displayed on Adafruit IO's dashboard for real-time monitoring.

## Benefits

  Preventive Maintenance: Early detection of issues helps prevent transformer failures.
  Cost Savings: Avoids costly repairs and downtime by maintaining transformer health.
  Reliability: Provides more accurate and reliable monitoring than traditional systems.
  Automation: Reduces the need for manual inspections, minimizing human dependency.

## Conclusion

The Real-Time Transformer Condition Observation System offers a robust solution for monitoring and controlling transformer health using IoT technology. By leveraging sensors, Raspberry Pi Pico W, and Adafruit IO, this system ensures high reliability, accuracy, and cost-effectiveness, significantly improving the traditional approach to transformer maintenance.

For more details, please refer to our published research paper: "Real-Time Transformer Condition Observing System" by Swati Aswale, Sumit Ingale, Namami Hire, and Rushikesh Bharade.
