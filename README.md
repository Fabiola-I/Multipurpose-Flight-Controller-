🛩️ Multipurpose Flight Controller (MFC)

The Multipurpose Flight Controller (MFC) is a custom-designed PCB that serves as the brain of drones, UAVs, and robotics systems. Built around a high-performance microcontroller, it integrates multiple sensors, communication modules, and power management features to support autonomous flight, payload control, and IoT/AI-based applications.

📌 Problem Statement

Most off-the-shelf flight controllers are either too basic (hobby-grade) or too expensive (industrial-grade). They also lack flexibility for custom research projects in IoT, AI, and robotics.

There is a need for an affordable, customizable, and research-ready flight controller that:

Supports multiple peripherals

Integrates sensors & communication modules

It is easy to program and expand

💡 Our Solution

The MFC PCB was designed to be multipurpose:

Compatible with drones, UAVs, and robotics platforms

Supports autonomous navigation, stabilization, and payload control

Provides interfaces for sensors, actuators, and communication modules

Enables IoT integration and AI-based decision-making

🚀 Features

✅ High-performance MCU (Teenesy board )

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

MCU: [👉 confirm exact chip, e.g., NXP i.MXRT1062 or HC32F4A0]

Sensors: MPU9250 (IMU), BMP280 (Barometer)

Connectivity: Zigbee module, USB Micro-B, UART, I²C, SPI

Outputs: 6–7 servo motor headers, MOSFET-driven terminal blocks

Power: USB-powered with regulated 3.3V & 5V outputs

<img width="1086" height="762" alt="Screenshot 2025-08-24 130033" src="https://github.com/user-attachments/assets/38b95585-0cfc-4578-aafa-41d7735f81f1" />
<img width="1083" height="764" alt="Screenshot 2025-08-24 130020" src="https://github.com/user-attachments/assets/2591fc62-b60b-4c5d-81c2-ee2234db20a4" />
<img width="1077" height="757" alt="Screenshot 2025-08-24 130005" src="https://github.com/user-attachments/assets/3c2fb4dc-0cfe-41c8-ba68-ef80ed40da29" />
<img width="1053" height="576" alt="Screenshot 2025-08-24 125950" src="https://github.com/user-attachments/assets/4b005380-8c98-416f-9c9c-fa2aa8df2e8b" />
<img width="1110" height="738" alt="Screenshot 2025-08-24 125937" src="https://github.com/user-attachments/assets/81148916-903a-4be1-aeb9-f8381524241b" />
<img width="1267" height="812" alt="Screenshot 2025-08-24 130231" src="https://github.com/user-attachments/assets/187a81de-da21-4fcf-be73-116559d81be3" />
<img width="590" height="648" alt="Screenshot 2025-08-24 130126" src="https://github.com/user-attachments/assets/0db39d81-9218-468f-9657-5ffe1fed6b7d" />
<img width="1091" height="779" alt="Screenshot 2025-08-24 130049" src="https://github.com/user-attachments/assets/ef12222b-d364-4ac9-acc9-560e18123db5" />


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



📊 Results & Applications

Stable flight control in drone prototypes

Integration with IoT platforms for telemetry

Can be used in:

UAVs and Drones

Agriculture sprayer drones

Robotics projects

Research & Education


🔮 Future Work

Add support for LiDAR and obstacle avoidance

Develop a dedicated dashboard for telemetry

Optimize AI integration for autonomous decision-making

Open-source community contribution

👥 Contributors

Fabiola Ingabire – Project Lead & PCB Designer
