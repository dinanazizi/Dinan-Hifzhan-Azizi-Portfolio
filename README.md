# Dinan Hifzhan Azizi

## Electronics and Instrumentation Graduate

### PCB Design | Embedded System | FPGA RTL | Hardware Development


Welcome to my engineering portfolio.

I am an Electronics and Instrumentation graduate with interests in PCB design, embedded systems, FPGA-based digital design, and hardware development.

My experience includes multilayer PCB development, MCU-based control systems, RTL design, hardware verification, IoT integration, and system testing.


# Technical Skills


## PCB & Hardware Design

- Schematic Design
- Component Selection
- PCB Layout and Routing
- Multilayer PCB Design
- ERC / DRC Verification
- Hardware Integration
- Hardware Testing


## Embedded Systems

- STM32
- ESP32 / ESP8266
- Embedded C/C++
- Sensor Integration
- UART
- I2C
- SPI
- MQTT


## FPGA & Digital Design

- Verilog HDL
- SystemVerilog
- RTL Design
- Finite State Machine (FSM)
- AXI4-Lite Interface
- FPGA Simulation and Verification


## Software, Cloud & Security

- Python
- Git
- AWS IoT Core
- Streamlit
- Apache Airflow
- Dremio
- MinIO
- Nessie
- Metabase



# Featured Projects


# PCB & Hardware Development


---

# 1. ESP32-Based IoT Gateway PCB Design


## Overview

A custom-designed four-layer IoT gateway hardware platform based on the ESP32-S3 microcontroller.

The project focuses on developing a modular hardware platform integrating communication interfaces, analog/digital expansion, industrial protocols, storage, and power management into a single PCB design.


## Main Contributions

- Developed hierarchical schematic design
- Participated in component selection and hardware architecture design
- Designed PCB placement and routing
- Integrated communication and peripheral interfaces
- Designed power management circuits
- Performed design rule verification


## Hardware Features


### Main Controller

- ESP32-S3 Microcontroller


### Communication Interfaces

- Ethernet Interface using W5500
- LTE Communication Interface
- RS-485 Interface
- CAN Bus Interface using SN65HVD230


### Data Acquisition

- ADS7128 Analog Input Expansion
- TCA9534 GPIO Expansion


### Storage

- MicroSD Card Interface


### Power Management

- 5V Input
- 3.3V Regulation
- TPS62132 Buck Converter
- Protection and filtering circuits


## PCB Specification

- Four-layer PCB
- Designed using Altium Designer
- Includes schematic design, component placement, routing, and verification


## Tools

- Altium Designer
- ESP32-S3


Repository:

https://github.com/dinanazizi/ESP32-Based-IoT-Gateway



---


# 2. IoT-Based Smart Office Energy Management System


## Undergraduate Thesis Project


## Overview

An IoT-based smart office energy management prototype developed using STM32F411 and ESP8266.

The system integrates PCB design, embedded firmware, sensor monitoring, automatic control, cloud communication, and secure MQTT authentication.


## Main Contributions

- Designed schematic and PCB layout
- Performed component selection and PCB verification
- Developed STM32 embedded firmware
- Integrated ESP8266 communication gateway
- Implemented AWS IoT Core communication
- Developed MQTT over TLS authentication
- Performed hardware testing and validation


## Hardware System


### Controller

- STM32F411 Edge Controller


### Communication Gateway

- ESP8266 WiFi Module


### Sensors

- PIR Occupancy Sensor
- DHT22 Temperature and Humidity Sensor
- ACS712 Current Sensor


### Control System

- Relay-based automatic control
- LED and 5V DC fan as simulation loads


## Communication Features

- UART communication between STM32 and ESP8266
- JSON telemetry
- CRC16 validation
- ACK/NACK handling
- Retry mechanism


## Security Implementation

Implemented:

- MQTT over TLS
- X.509 certificate authentication


## Testing Results

| Parameter | Result |
|---|---|
| Energy reduction | 32.03% |
| Unique packets transmitted | 1,520 |
| Transmission success rate | 100% |
| Average latency | 245 ms |


## Tools

- Autodesk EAGLE
- STM32F411
- ESP8266
- AWS IoT Core
- Node-RED
- InfluxDB
- Grafana


Repository:

https://github.com/dinanazizi/Authenticated-IoT-Smart-Office-STM32-ESP8266





# Digital Design & FPGA Projects


---


# 3. FPGA Secure Boot Status Monitoring Peripheral


## Overview

A Verilog RTL project implementing a secure-boot status monitoring peripheral for a Zynq-7000 FPGA platform.

The design monitors boot authentication status, stores results, provides AXI4-Lite register access, and generates system status indications.


## Main Contributions

- Designed RTL modules using Verilog/SystemVerilog
- Implemented boot monitoring FSM
- Developed AXI4-Lite register interface
- Designed authentication status monitoring logic
- Implemented error-code storage
- Verified RTL functionality through simulation and synthesis


## Features

- AXI4-Lite register interface
- FSM-based boot monitoring
- Authentication failure latch
- Error-code storage
- Status monitoring output


## Design Flow


RTL Design
      |
Simulation
      |
Synthesis
      |
Timing Analysis


## Tools

- AMD Vivado
- Verilog/SystemVerilog
- XSim


## Target Platform

- Xilinx Zynq-7000 (XC7Z045)


Repository:

https://github.com/dinanazizi/FPGA-Secure-Boot-RTL



---


# 4. FPGA-Based NMEA Parser via UART


## Overview

An FPGA-based NMEA parser developed using Verilog HDL.

The system receives GPS NMEA sentences through UART communication, processes incoming data using FSM logic, validates checksum, and transmits parsing results back through UART.


## System Architecture


PC Python Serial Sender
          |
          |
FTDI USB-TTL Converter
          |
          |
UART RX
          |
          |
NMEA Parser FSM
          |
          |
UART TX
          |
          |
Serial Monitor


## Main Contributions

- Designed UART communication module using Verilog HDL
- Implemented FSM-based NMEA parsing
- Developed start detection and field extraction logic
- Implemented real-time XOR checksum validation
- Designed UART receive and transmit flow
- Performed hardware debugging using status indicators


## Features

- UART communication at 115200 baud rate
- Start character detection
- Field extraction
- Checksum validation
- Bidirectional serial communication
- FSM-based processing


## Tools

- Verilog HDL
- AMD Vivado
- XSim
- Python Serial Communication


Repository:

https://github.com/dinanazizi/FPGA-Based-NMEA-Parser-using-UART





# Software, Data & Security Projects


---


# 5. macOS HIDS, RGC Engine & Streamlit Dashboard


## Overview

A cybersecurity monitoring project combining a macOS Host-based Intrusion Detection System (HIDS), Risk Governance and Compliance (RGC) engine, and Streamlit dashboard.

The system monitors file changes, detects system anomalies, maps security events to governance requirements, and visualizes risk status.


## Main Features


### Host-based Intrusion Detection System (HIDS)

- Monitors file changes
- Detects abnormal system activities
- Tracks security-related events


### Risk Governance & Compliance (RGC) Engine

- Maps security events into risk categories
- Supports compliance monitoring workflow
- Provides risk evaluation information


### Streamlit Dashboard

- Visualizes system monitoring results
- Displays risk and compliance status
- Provides real-time monitoring interface


## Technologies

- Python
- Streamlit
- macOS Security Monitoring
- Risk Governance & Compliance


Repository:

https://github.com/dinanazizi/macos-hids-rgc-dashboard





---
