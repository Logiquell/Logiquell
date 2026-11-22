# Mechatronics Engineer | Embedded Systems & Electromechanical Design

I'm a B.Sc. graduate in Mechatronics Engineering from the University of Iceland, with a background in mechanical maintenance, industrial equipment, fleet operations and technical troubleshooting.

I also hold a Master Automotive Mechanic qualification, combining extensive hands-on mechanical experience with engineering knowledge in electronics, programming, automation and control systems.

My main interests are developing, building and testing systems that combine mechanical components, electronics and software.

## Engineering Projects

### 1. Automatic Toe-In Alignment System
**B.Sc. Final Year Project | University of Iceland**

Designed, built and experimentally evaluated an automatic toe-in alignment prototype for a four-wheel-steering system.

The system uses an ESP32 microcontroller, infrared emitters and photodiodes, and servo-controlled steering mechanisms to automatically determine wheel alignment.

**Key features:**
- ESP32-based control system
- Infrared sensor integration and signal processing
- Automated coarse and fine alignment routines
- Servo motor control using PWM
- Experimental testing and performance evaluation

**Results:**
- 30 experimental tests conducted
- Mean absolute alignment errors between 0.35° and 2.19° across the four wheels
- All four wheels achieved mean absolute errors below 3°

**Published thesis:** [Automatic Toe-In Alignment System – Skemman, University of Iceland](https://skemman.is/handle/1946/51741)

### 2. PIC-Based Fall Detector & Environmental Data Logger
**Fallskynjari | November 2026 | Ongoing**

Developing a battery-powered embedded device using a PIC16LF1559 microcontroller to detect free-fall events and record environmental measurements.

**Key features:**
- ADXL345 accelerometer for free-fall detection
- AHT20 temperature and humidity sensor
- I²C communication with sensors, OLED display and external EEPROM
- Temperature and humidity logging at three-minute intervals
- Interrupt-driven event detection
- Checksummed EEPROM records and CSV export over UART
- Watchdog-based wake-up and low-power firmware design

**Engineering challenges:**
- Developing firmware within 512 bytes of RAM
- Managing multiple I²C peripherals
- Implementing reliable data storage
- Balancing periodic measurements with low-power operation

**Current status:** Integrated firmware is undergoing testing. Battery-powered operation and real-world fall detection remain to be validated.

### 3. ESP32-S3 Smartwatch Firmware
**Waveshare ESP32-S3-Touch-AMOLED-2.06 | November 2026 | Ongoing**

Developing custom firmware for an ESP32-S3 smartwatch using Espressif's ESP-IDF framework and the LVGL graphics library.

**Key features:**
- Custom AMOLED watch faces
- Wi-Fi time synchronization using NTP
- Battery monitoring through the AXP2101 power-management IC
- Time retention using the PCF85063 real-time clock
- Display sleep and CPU light-sleep management
- Persistent crash diagnostics and restart tracking

**Engineering challenges:**
- Debugging SPI display transfer issues
- Optimizing LVGL memory allocation
- Resolving unexpected CPU wake-ups
- Reducing unnecessary Wi-Fi activity
- Optimizing standby power consumption

**Measured improvement:** Reduced observed standby battery drain from approximately 12% per hour to 3% per hour, with the CPU in light sleep approximately 97% of the time.

**Current development:** Motion-based wake-up, touchscreen navigation, step counting and further battery-life testing.

## Technical Skills

| Area | Technologies & Experience |
|---|---|
| Microcontrollers | ESP32, ESP32-S3, PIC16LF1559 |
| Programming | C, C++, Python (foundational working knowledge) |
| Development environments | ESP-IDF, PlatformIO, Arduino IDE, MPLAB X |
| Communication | I²C, SPI, UART, Wi-Fi, TCP/IP |
| Electronics | Soldering, PCB assembly, circuit prototyping, sensors |
| Measurement equipment | Multimeters, oscilloscopes, laboratory power supplies |
| Motor control | DC motors, stepper motors, servos, PWM |
| Mechanical design | Autodesk Inventor, AutoCAD |
| Industrial systems | Pumps, compressors, hydraulics, pneumatics, mechanical troubleshooting |
| Electrical engineering | Electric motors, theoretical knowledge of three-phase systems and VFDs |

## Engineering Approach

My experience combines practical mechanical troubleshooting with electronics and embedded systems development.

I focus on understanding how systems work, identifying problems, developing solutions and validating them through testing.

I use AI-assisted development tools, including Claude Code, to support programming, debugging and documentation. My programming skills are still developing, and I focus on understanding the code, integrating hardware and verifying functionality through practical tests.

## Current Focus

I'm continuing to develop my skills in:

- Embedded C/C++ programming
- Sensor integration and data acquisition
- Industrial instrumentation and control systems
- Low-power embedded design
- Mechanical design and electromechanical prototyping
- Hardware testing and validation

## Education & Background

**B.Sc. Mechatronics Engineering**  
University of Iceland

**Master Automotive Mechanic Qualification**  
Iceland

Professional experience includes heavy-duty vehicle maintenance, industrial equipment troubleshooting, fleet supervision, electronics assembly and technical operations management.

---

**Published academic work:** [Automatic Toe-In Alignment System – Skemman](https://skemman.is/handle/1946/51741)
