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
<img width="1065" height="750" alt="Screenshot 2025-08-24 124227" src="https://github.com/user-attachments/assets/629dcefa-8ead-408a-a455-c8d13f865dd6" />

<img width="487" height="640" alt="Screenshot 2025-08-24 124248" src="https://github.com/user-attachments/assets/9bd407b0-bb0a-41ed-8ba5-fab86239f5ce" />



🛠️ Hardware Design
<img width="853" height="739" alt="Screenshot 2025-08-24 124322" src="https://github.com/user-attachments/assets/e52b6478-6a7f-42cf-8e39-fca3dec37945" />

<img width="739" height="743" alt="Screenshot 2025-08-24 124340" src="https://github.com/user-attachments/assets/e4ea728e-baf7-4cc1-8d8f-86728c3562e2" />

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

Connect hardware:

Servo motors to PWM headers

Sensors (MPU9250, BMP280) to I²C

Zigbee module via SPI/UART

GPS to UART

Upload firmware and test stabilization/sensor readings.

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
