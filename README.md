# Smart Gamified Physiotherapy System

## 📖 What is this project?
This is a smart, interactive physiotherapy system designed for at-home use. We built this for a C-DAC health-tech hackathon attended at RSET College, Kerala. 

Instead of doing boring exercises, a patient wears our hardware. The sensors track their body movements and turn their physiotherapy into a computer game. If they do the exercise wrong, the hardware vibrates (haptic feedback) to correct their posture in real-time.

## 🛠️ My Role: Project Lead & Hardware Engineer
I led this project and personally built the entire hardware and embedded systems layer:

* **Built the Hardware:** I wired and integrated the microcontrollers (ESP32 and the C-DAC VEGA ARIES v2.0) with motion sensors (IMU), bend sensors for the fingers (Flex), and muscle sensors (EMG).
* **Wrote the Firmware:** I wrote the C/C++ code that reads the patient's body movements and controls the vibration motors.
* **Connected Hardware to Software:** I built the communication pipeline that successfully sends the live physical data from the hardware to the computer game.

## 📂 What is inside these folders?
* **`/esp32_firmware` & `/vega_aries_firmware`**: The C/C++ code running on the physical hardware boards.
* **`/arm_tracker`**: The logic that calculates exactly where the patient's arm is in 3D space.
* **`/hand_rehab`**: Programs specifically for tracking finger bends and grip strength.
* **`/rehab_system`**: The main game interface the patient interacts with.

## ⚙️ Tools & Tech Used
* **Boards:** ESP32, VEGA ARIES v2.0 (C-DAC)
* **Sensors:** BNO08x (Motion/IMU), Flex Sensors, EMG (Muscle)
* **Languages:** C/C++ for hardware, Python for data tracking

## 🤝 The Team
I led the hardware architecture, while the front-end game UI and visual tracking algorithms were developed alongside my teammates.
