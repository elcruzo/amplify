# Python Speech Recognition Tool

Welcome to this repository containing a Speech Recognition Tool.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Customizations](#customizations)
- [Contributions](#contributions)
- [License](#license)

## Introduction

The Python Speech Recognition Tool is a simple script that uses the SpeechRecognition library to convert spoken language into written text. It allows you to interact with your computer using voice commands and can be customized to perform various tasks based on voice input.

## Features

- Convert spoken language into text using Google's speech recognition API.
- Continuously listens for voice input, making it suitable for interactive voice commands.
- Handles ambient noise by adjusting for it before recognition.

## Requirements

To use this script, you need the following:

- Python 3.8 and above
- The `SpeechRecognition` library, which can be installed using pip:
  
  ```bash
  pip install speechrecogntion
  ```
  
- The `text-to-speech` conversion library, which can be installed using pip:
  
  ```bash
  pip install pyttsx3
  ```
  
- The `PyAudio` library, which is required for microphone access and can be installed using pip:
  
  ```bash
  pip install pyaudio
  ```
  
- An active network connection
- Two computers or instances to act as the sender and receiver

## Installation

1. Clone this repository or download the ZIP file and extract it to your preferred location.

   ```bash
   git clone https://github.com/elcruzo/elcruzo-speech-recognition.git
   ```
   
2. Navigate the project directory:
   
   ```bash
   cd elcruzo-speech-recognition
   ```
   
3. Ensure you have Python 3.x installed. You can check by running:

   ```bash
   python3 --version
   ```

   If Python is not installed, you can download it from the official [Python website](https://www.python.org/downloads/).

4. You are now ready to use the tool.

## Usage

Receiver (receiver.py)

1. Run the script using the following command:

   ```bash
   python index.py
   ```

2. The script will continuously listen for your voice input using the microphone.
3. When you speak, the tool will attempt to recognize your speech and display the recognized text in lowercase.
3. To stop the tool, press `Ctrl+C` in the terminal where the script is running.

## Customization

You can customize the behavior of the tool by modifying the script (`index.py`). You can add logic to perform specific tasks based on recognized voice commands. For example, you could integrate the tool with other applications, control your computer, or automate tasks.

## Contributions
Contributions to this repository are welcome! If you have any improvements or feature suggestions, feel free to fork this repository, make your changes, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Have fun exploring my Speech Recognition tool! If you have any questions or run into issues, don't hesitate to ask for help.


