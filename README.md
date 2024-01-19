# P2-LED-OPEN-USING-VOICE






 TinyML Voice-Activated LED Control on Arduino



ANKIT KUMAR 2021UCA1835
PRANAY BHARDWAJ 2021UCA1856
ANKUSH DHANKHAR 2021UCA1965















Table of Contents

1. Introduction
2. Project Overview
3. Hardware Requirements
4. Software Requirements
5. Installation
6. Usage
7. Troubleshooting
8. Conclusion
9. Resources

1. Introduction

Welcome to the TinyML Voice-Activated LED Control project documentation. This project demonstrates how to control a P2 LED using voice commands on an Arduino board. TinyML (Tiny Machine Learning) is utilized to recognize specific voice commands and trigger the corresponding action.

 2. Project Overview

The project involves setting up a microphone sensor to capture voice input, implementing a TinyML model to recognize predefined voice commands, and controlling a P2 LED based on the recognized commands.

3. Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- P2 LED module
- Microphone sensor
- Jumper wires
- Breadboard

 4. Software Requirements

- Arduino IDE
- TensorFlow Lite for Microcontrollers Library
- Edge Impulse Studio account (for training TinyML model)

5. Installation

Follow these steps to set up the project:

1. Connect the microphone sensor and P2 LED module to the Arduino board using jumper wires and a breadboard.

2. Install the Arduino IDE on your computer.

3. Install the TensorFlow Lite for Microcontrollers Library in the Arduino IDE.

4. Create an account on Edge Impulse Studio (https://www.edgeimpulse.com/) and follow the instructions to train a TinyML model for voice recognition.

5. Download the trained model from Edge Impulse and import it into the Arduino IDE.

6. Upload the Arduino sketch provided in the project repository to the Arduino board.

 6. Usage

1. Power up the Arduino board.

2. Speak the predefined voice commands (e.g., "LED on" or "LED off") within the range of the microphone sensor.

3. The TinyML model will recognize the command, and the P2 LED will respond accordingly.

7. Troubleshooting

- If the P2 LED does not respond to voice commands, ensure that the connections are correct, and the microphone is functioning.

- Check the serial monitor in the Arduino IDE for any error messages or debugging information.

8. Conclusion

Congratulations! You have successfully set up a TinyML project for voice-activated LED control on an Arduino board. Experiment with different voice commands and adapt the project for your specific needs.

 9. Resources

- Arduino Official Website: https://www.arduino.cc/
- TensorFlow Lite for Microcontrollers Library: https://www.arduino.cc/en/Guide/TensorFlowLite
- Edge Impulse Studio: https://www.edgeimpulse.com/
- Project Repository (GitHub): https://github.com/dev-ankit-kumar/P2-LED-OPEN-USING-VOICE

