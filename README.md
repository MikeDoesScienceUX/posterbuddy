# Scientific Poster Visit Counter

## Purpose
The purpose of this project is to create a device that counts entrances and exits to a row of scientific posters, as well as visits to individual scientific posters during poster sessions.

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Hardware Requirements](#hardware-requirements)
4. [Assembly Instructions](#assembly-instructions)
5. [Software Setup](#software-setup)
6. [Usage](#usage)
7. [License](#license)

## Introduction
This project aims to provide an open hardware solution for tracking the number of visitors to scientific posters. It uses simple components to create an effective counting mechanism for scientific events.

## Features
- Counts entrances and exits for a row of posters.
- Tracks visits to individual scientific posters.
- Simple and cost-effective components.

## Hardware Requirements
- Arduino
- Extension board
- Sonar sensor (could also use radar or other sensors)
- Battery
- OLED screen

## Assembly Instructions
**Note:** Add images or diagrams in the placeholders below for better clarity.

1. **Connect the Sonar Sensor**
   - Connect the sonar sensor to the extension board.
   - ![Sonar Sensor Connection](link-to-image)

2. **Attach the OLED Screen**
   - Connect the OLED screen to the extension board.
   - ![OLED Screen Connection](link-to-image)

3. **Power the Device**
   - Connect the battery to the Arduino and extension board.
   - ![Battery Connection](link-to-image)

4. **Mount the Components**
   - Assemble the components in a suitable enclosure or mount them on a board.
   - ![Final Assembly](link-to-image)

## Software Setup
1. **Install Arduino IDE**
   - Download and install the Arduino IDE from [Arduino's official website](https://www.arduino.cc/en/Main/Software).

2. **Download the Code**
   - Clone or download the code from this repository.

3. **Upload the Code**
   - Open the downloaded code in the Arduino IDE.
   - Connect the Arduino to your computer via USB.
   - Upload the code to the Arduino.

## Usage
1. **Power On the Device**
   - Turn on the device by connecting the battery.

2. **Position the Device**
   - Place the device at the entrance of the poster row and near individual posters as needed.

3. **Monitor the Visits**
   - The OLED screen will display the count of entrances, exits, and visits to individual posters.

## License
This project is licensed under the [Open Hardware License](link-to-license).

---