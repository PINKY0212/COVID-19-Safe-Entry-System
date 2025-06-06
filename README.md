# COVID-19-Safe-Entry-System

In the wake of the COVID-19 pandemic, public health regulations such as mask mandates and body temperature checks have become essential for safe entry into buildings, offices, and public spaces. However, manual enforcement of these measures is inefficient, prone to human error, and increases the risk of exposure for security personnel. To address these challenges, we present "THE SENTINEL"—an intelligent, automated entry system designed to enforce safety protocols while maintaining accurate occupancy records in real time.

THE SENTINEL is a smart entry system that integrates IoT sensors and deep learning to ensure compliance with COVID-19 safety norms. It automates temperature screening, mask detection, and sanitization while maintaining a secure log of entries and exits. By reducing human intervention, the system enhances efficiency, minimizes infection risks, and ensures a contactless verification process.

## Key Features & Functionalities

- **Automated Temperature Screening**
A non-contact infrared (IR) thermal sensor measures body temperature in real time.
If a person’s temperature exceeds the safe threshold, the system denies entry and triggers an alert.

- **Face Mask Detection**
A deep learning model (using OpenCV, TensorFlow/Keras, or PyTorch) analyzes live camera feed to detect whether a person is wearing a mask.
If no mask is detected, access is denied, and a visual/audio alert notifies the individual.

- **Touchless Sanitization Dispenser**
An ultrasonic or motion sensor activates an automatic sanitizer dispenser upon entry, ensuring hand hygiene before access.
Real-Time People Counting & Occupancy Tracking

- **Using IR sensors, the system logs entry and exit timestamps**
A centralized dashboard displays the real-time count of people inside the building, preventing overcrowding.

## Technical Implementation
**Hardware:** Raspberry Pi/Arduino, IR temperature sensor, ultrasonic sensor, servo motor (for gate control), camera module.
**Software:** Python (OpenCV, TensorFlow), Flask/Django for dashboard, Firebase/MySQL for data storage.
**Deep Learning Model:** Custom CNN (Convolutional Neural Network) trained on masked/unmasked face datasets.
