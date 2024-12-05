# Safety Night Patrolling Robot

The **Safety Night Patrolling Robot** is an IoT-based surveillance solution designed to enhance security in areas where human presence is limited. This robot leverages AI-driven algorithms for real-time surveillance, human detection, and path planning, making it an efficient alternative to traditional security systems.

## Features

### Autonomous Patrolling
- Utilizes **AI algorithms** for path detection and navigation.
- Detects and avoids obstacles using sensors.

### Real-Time Surveillance
- Equipped with **ESP32-CAM** for live video streaming.
- Captures and processes images or video in real time.

### Human Detection
- Integrates pre-trained **MobileNet SSDlite v2** for human and object recognition.
- Triggers alerts upon detecting suspicious activity.

### Remote Operation
- Controlled via **Android application**.
- Supports wireless connectivity through **Wi-Fi** and IoT integration.


## AI Capabilities

1. **Human Detection**:
   - Pre-trained MobileNet SSDlite v2 for object recognition.
   - Efficient and lightweight for on-device processing.

2. **Path Detection**:
   - Uses image processing techniques (edge and line detection) to navigate paths and avoid obstacles.


## How It Works

1. **Setup**:
   - Program the ESP32-CAM using the FTDI module.
   - Assemble the components onto the robotic chassis.
2. **Operation**:
   - The robot captures images and streams real-time video.
   - AI algorithms process the visuals for path detection and human identification.
   - Users control the robot via the Android app, adjusting movement and monitoring the environment.


## Advantages

- **24/7 Surveillance**: Operates continuously without the need for human intervention.
- **Cost-Efficiency**: Reduces labor costs and leverages affordable hardware.
- **Versatile Deployment**: Suitable for homes, industries, public areas, and restricted zones.
- **Enhanced Safety**: Mitigates risks to human security personnel.



**Working Video link:** https://drive.google.com/drive/folders/1804CerHP8__lEwbodb3ZN1wvfvQ0QF-x
