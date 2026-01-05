# Vocal Gesture Recognition Glove

## Problem Statement
Speech-impaired and paralyzed individuals often struggle to communicate basic needs.
This project aims to convert simple hand gestures into readable text output, enabling
basic communication without speech.

## System Overview
The system uses flex sensors mounted on a glove to detect finger bending.
Each gesture produces a unique voltage pattern which is mapped to predefined messages
displayed on an LCD screen.

## Sensors and Components Used
- Flex Sensors (for finger bend detection)
- Arduino Uno (microcontroller)
- 16x2 LCD Display
- Bluetooth Module (optional, future extension)
- Battery Pack

### Why Flex Sensors?
Flex sensors provide a low-cost and simple method to capture finger movement.
They are suitable for basic gesture classification without complex signal processing.

## Gesture Mapping Logic
1. Finger bending changes the resistance of flex sensors
2. Analog voltage values are read by Arduino
3. Threshold-based logic classifies gestures
4. Corresponding text message is displayed on the LCD

Example:
- Gesture 1 → "I need food"
- Gesture 2 → "I need help"
- Gesture 3 → "How are you"

## Results
The prototype successfully detects predefined gestures and displays the
corresponding message in real time on the LCD.

## Limitations
- Works only for predefined gestures
- No machine learning used
- Accuracy depends on sensor placement
- Not suitable for complex sign language

## Future Improvements
- Machine learning-based gesture classification
- IMU sensors for motion tracking
- Camera-based vision system
- Mobile app integration for speech output

## Applications
- Assistive technology for speech-impaired users
- Human-computer interaction research
- Educational embedded systems projects
