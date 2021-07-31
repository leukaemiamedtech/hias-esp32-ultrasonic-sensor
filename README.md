# Peter Moss Acute Myeloid & Lymphoblastic Leukemia AI Research Project
## HIAS ESP32 Ultrasonic Sensor

![HIAS ESP32 Ultrasonic Sensor](assets/images/project-banner.jpg)

[![CURRENT RELEASE](https://img.shields.io/badge/CURRENT%20RELEASE-1.0.0-blue.svg)](https://github.com/AIIAL/HIAS-ESP32-Ultrasonic-Sensor/tree/1.0.1) [![UPCOMING RELEASE](https://img.shields.io/badge/CURRENT%20DEV%20BRANCH-2.0.0-blue.svg)](https://github.com/AIIAL/HIAS-ESP32-Ultrasonic-Sensor/tree/2.0.0) [![Contributions Welcome!](https://img.shields.io/badge/Contributions-Welcome-lightgrey.svg)](CONTRIBUTING.md)  [![Issues](https://img.shields.io/badge/Issues-Welcome-lightgrey.svg)](issues)

[![Documentation Status](https://readthedocs.org/projects/hias-esp32-ultrasonic-sensor/badge/?version=latest)](https://hias-esp32-ultrasonic-sensor.readthedocs.io/en/latest/?badge=latest)
 [![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/5086/badge)](https://bestpractices.coreinfrastructure.org/projects/5086)

![Unit Tests](https://img.shields.io/badge/Unit%20Tests-TODO-red)
![Functional Tests](https://img.shields.io/badge/Functional%20Tests-TODO-red)

 [![LICENSE](https://img.shields.io/badge/LICENSE-MIT-blue.svg)](LICENSE)

&nbsp;

# Introduction

Ultrasonic sensors can play a large role in Internet of Things (IoT) security systems. This project shows the potential of using an ESP32 to host a Bluetooth Low Energy (BLE) server providing readings from an ultrasonic sensor to a HIAS BLE IoT Agent.

![HIAS ESP32 Ultrasonic Sensor](assets/images/hias-esp32-ultrasonic-sensor.gif)

The server waits for a HIAS BLE IoT Agent to connect and provides it with the current reading of the ultrasonic sensor. The BLE IoT Agent next verifies the server has permissions to store data on the HIAS network via the HIASBCH iotJumpWay permissions smart contract.

![HIAS BLE Network](assets/images/hias-ble-network.jpg)

Once the server is verified, the BLE IoT Agent processes the sensor data, updates the related contextual data and stores the data in the historical database.

&nbsp;

# Hardware

 - [ESP32 Devkit](https://docs.espressif.com/projects/esp-idf/en/latest/esp32s2/hw-reference/esp32s2/user-guide-saola-1-v1.2.html)
 - [Elegoo HC-SR04 Ultrasonic Sensor](https://www.elegoo.com/products/elegoo-uno-project-super-starter-kit)
 - Wires

&nbsp;

# Software

 - [Arduino IDE](https://www.arduino.cc/en/software)
 - [Arduino-ESP32](https://github.com/espressif/arduino-esp32)
 - [HIAS ESP32 Ultrasonic Sensor](arduino/HIAS-Ultrasonic-Sensor)

&nbsp;

# Getting Started

To set up and install your HIAS ESP32 Ultrasonic Sensor follow the following guides.

- [Installation guide](docs/installation/installation.md)

&nbsp;

# Contributing
Asociación de Investigacion en Inteligencia Artificial Para la Leucemia Peter Moss encourages and welcomes code contributions, bug fixes and enhancements from the Github community.

Please read the [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") document for a full guide to contributing to our research project. You will also find our code of conduct in the [Code of Conduct](https://github.com/AIIAL/Contributing-Guide/blob/main/CODE-OF-CONDUCT.md) document.

## Contributors
- [Adam Milton-Barker](https://www.leukemiaairesearch.com/association/volunteers/adam-milton-barker "Adam Milton-Barker") - [Asociación de Investigacion en Inteligencia Artificial Para la Leucemia Peter Moss](https://www.leukemiaresearchassociation.ai "Asociación de Investigacion en Inteligencia Artificial Para la Leucemia Peter Moss") President/Founder & Lead Developer, Sabadell, Spain

&nbsp;

# Versioning
We use [SemVer](https://semver.org/) for versioning.

&nbsp;

# License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE "LICENSE") file for details.

&nbsp;

# Bugs/Issues
We use the [repo issues](issues "repo issues") to track bugs and general requests related to using this project. See [CONTRIBUTING](CONTRIBUTING.md "CONTRIBUTING") for more info on how to submit bugs, feature requests and proposals.