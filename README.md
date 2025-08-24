🛩️ Multipurpose Flight Controller (MFC)

The Multipurpose Flight Controller (MFC) is a custom-designed PCB that serves as the brain of drones, UAVs, and robotics systems. Built around a high-performance microcontroller, it integrates multiple sensors, communication modules, and power management features to support autonomous flight, payload control, and IoT/AI-based applications.

📌 Problem Statement

Most off-the-shelf flight controllers are either too basic (hobby-grade) or too expensive (industrial-grade). They also lack flexibility for custom research projects in IoT, AI, and robotics.

There is a need for an affordable, customizable, and research-ready flight controller that:

Supports multiple peripherals

Integrates sensors & communication modules

Is easy to program and expand

💡 Our Solution

The MFC PCB was designed to be multipurpose:

Compatible with drones, UAVs, and robotics platforms

Supports autonomous navigation, stabilization, and payload control

Provides interfaces for sensors, actuators, and communication modules

Enables IoT integration and AI-based decision-making

🚀 Features

✅ High-performance MCU (NXP i.MXRT / STM32 / ESP32-based [👉 confirm])

✅ 6–8 servo motor control (PWM outputs)

✅ Integrated sensors (IMU MPU9250, barometer BMP280)

✅ Communication modules (Zigbee, GPS, USB, UART, I2C, SPI, CAN)

✅ Power management with USB & regulated outputs (3.3V / 5V)

✅ Support for MOSFET-driven terminal blocks for external loads

✅ Expandable & open-source design

🏗️ System Architecture
       Sensors (IMU, Barometer, GPS, etc.)
                       ↓
        Multipurpose Flight Controller PCB
   (MCU + Power Mgmt + Communication Interfaces)
                       ↓
        Actuators (Motors, Servos, Terminal Blocks)
                       ↓
        Communication (Zigbee, USB, IoT Platform)


📷 (Insert PCB block diagram / schematic image here)

🛠️ Hardware Design

MCU: [👉 confirm exact chip, e.g., NXP i.MXRT1062 or HC32F4A0]

Sensors: MPU9250 (IMU), BMP280 (Barometer)

Connectivity: Zigbee module, USB Micro-B, UART, I²C, SPI

Outputs: 6–7 servo motor headers, MOSFET-driven terminal blocks

Power: USB-powered with regulated 3.3V & 5V outputs

📷 (Insert PCB 3D render & schematic here)

🤖 Software Support

Compatible with Arduino IDE / PlatformIO

Support for ArduPilot / PX4 firmware [👉 confirm if you tested]

Custom drivers for servo control, sensors, and Zigbee

Machine Learning integration (optional AI decision-making layer)

⚙️ Installation & Usage

Clone the repository:

git clone https://github.com/YourUsername/MultipurposeFlightController.git
cd MultipurposeFlightController


Open the firmware in Arduino IDE / PlatformIO.

Connect hardware:

Servo motors to PWM headers

Sensors (MPU9250, BMP280) to I²C

Zigbee module via SPI/UART

GPS to UART

Upload firmware and test stabilization / sensor readings.

📊 Results & Applications

Stable flight control in drone prototypes

Integration with IoT platforms for telemetry

Can be used in:

UAVs and Drones

Agriculture sprayer drones

Robotics projects

Research & Education

📷 (Insert hardware testing images here)

🔮 Future Work

Add support for LiDAR and obstacle avoidance

Develop a dedicated dashboard for telemetry

Optimize AI integration for autonomous decision-making

Open-source community contribution

👥 Contributors

Fabiola Ingabire – Project Lead & PCB Designer
Ipyana Mwaisekwa- Team Leader 
