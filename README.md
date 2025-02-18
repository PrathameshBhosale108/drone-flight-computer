# 🚀 Drone Flight Computer

## 📌 Overview
This repository contains the firmware for a **drone flight computer** using the **Raspberry Pi Pico WH** and **MicroPython**. The firmware handles **PID control, sensor data processing, motor control via PWM**, and **wireless communication** for remote control.

## 🛠 Features
- **PID Controller** for stable flight
- **IMU Sensor Data Processing** (e.g., MPU6050, BMI160)
- **PWM Motor Control** for quadcopter motors
- **WiFi/Bluetooth Communication** for remote control
- **Failsafe Mechanism** to prevent crashes

## 🏗 Hardware Requirements
- **Raspberry Pi Pico WH**
- **MPU6050** (IMU Sensor)
- **ESCs & Brushless Motors**
- **LiPo Battery**
- **HC-05 Bluetooth Module** (optional)

## 📜 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/drone-flight-computer.git
   cd drone-flight-computer
   ```
2. Install **MicroPython** on your **Raspberry Pi Pico WH**.
3. Upload the firmware to the Pico using **Thonny** or **mpremote**:
   ```sh
   mpremote cp main.py :/main.py
   ```

## 📂 Project Structure
```
.
├── main.py         # Main flight control script
├── pid.py          # PID controller implementation
├── motor.py        # Motor control functions
├── imu.py          # IMU sensor data processing
├── communication.py # WiFi/Bluetooth communication
└── README.md       # Project documentation
```

## 🎮 Usage
1. Power on the Raspberry Pi Pico WH.
2. Connect via **WiFi/Bluetooth** for remote commands.
3. The flight computer will initialize sensors and start **motor control**.

## 📌 To-Do
- [ ] Improve PID tuning
- [ ] Add GPS support
- [ ] Implement failsafe mechanisms

## 🏗 Contributing
Contributions are welcome! Feel free to open an **issue** or **pull request**.

## 📜 License
MIT License. See `LICENSE` for details.

---
**Made with ❤️ by Our Team**

