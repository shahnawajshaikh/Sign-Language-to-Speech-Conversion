# Sign Language to Speech Conversion for Mute People

Sign Language to Speech Conversion is an assistive communication system designed to help individuals with speech impairments communicate more effectively. The project translates predefined hand gestures into spoken words using a wearable glove equipped with flex sensors and an MPU6050 motion sensor.

The system is powered by an ESP32 microcontroller, which collects finger movement and hand orientation data to recognize specific gestures. Once a gesture is identified, the corresponding text is transmitted wirelessly via Bluetooth to a custom Android Text-to-Speech (TTS) application developed using MIT App Inventor. The application converts the received text into audible speech in real time, enabling seamless communication with people who do not understand sign language.

This project demonstrates the integration of embedded systems, sensor technology, Bluetooth communication, and mobile application development to create a portable, low-cost, and user-friendly assistive device. It was developed as a Final Year Engineering Project in 2023 with the goal of improving accessibility and promoting inclusive communication.
