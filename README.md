# SignScribe
Raspberry Pi 4B Based Sign Language Interpreter

> This project was developed for the laboratory session in the Electronics in Service to Society Lab for the academic year 2023-24, as part of the coursework requirement.

## Aim
The primary objective of the ***SignScribe*** project is to develop a Sign Language Interpreter using a Raspberry Pi 4B with a USB camera. The project aims to contribute to the United Nations Sustainable Development Goals (SDGs), specifically targeting **SDG 4 - Quality Education** and **SDG 10 - Reduced Inequalities**.

By leveraging the capabilities of the Raspberry Pi 4B and a quality web camera, the SignScribe team seeks to create a technological solution that can interpret and translate sign language gestures in real-time, to text as well as speech.

Through the development of ***SignScribe***, the team aspires to empower individuals with hearing and visual impairments and foster a more inclusive society where communication is accessible to all.

## Schematic
![image](https://github.com/bazingamofos/SignScribe/assets/69231405/0f55ea17-704f-4c3f-b0aa-a775d13f491f)

## Hardware Setup
![WhatsApp Image 2024-05-15 at 10 24 42 PM](https://github.com/bazingamofos/SignScribe/assets/69231405/de812f2f-13f5-4c92-aa18-41be5733430d)

![d226d3db-14ce-4b6a-9370-ae3ceccff9ed](https://github.com/bazingamofos/SignScribe/assets/69231405/96039f51-bbc5-493a-bb21-d02807a3b05c)

## Implementation

### Raspberry Pi Setup
* Initial setup of Raspberry Pi 4B and installation of a suitable environment for code implementation.

### Modelling
* Creation of a dataset for Indian sign language gestures.
* Importing necessary libraries for data processing.
* Specifying the path for storing images.
* Designing the model structure, utilizing a pose-based deep learning model with LSTM for sequential data processing.
* Training the model and evaluating its performance on test data, achieving an accuracy rate of 85-90%.

### Testing
* Importing required libraries for implementation of Mediapipe.
* Implementation of pose estimation using Mediapipe for real-time gesture recognition.
* Integration of the trained recognition model with the system.

### User Interface
* Installation of necessary libraries for I2C LCD interfacing.
* Interfacing the LCD with Raspberry Pi to visually display text output.
* Installation of necessary libraries ( for text-to-speech (TTS) functionality.
* Writing code to convert text output into speech, enabling users to hear the interpreted signs through wired earphones connected to the audio jack.

## Credits 
This project includes code from Swaroop Srisailam's `Continuous-Indian-Sign-Language-Recognition`.


