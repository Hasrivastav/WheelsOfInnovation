#libraries explaination
AsyncTCP.h: Library for asynchronous TCP communications.
ESPAsyncWebServer.h: Library for creating an asynchronous web server on the ESP32.
iostream and sstream: Standard C++ input/output stream libraries.
ESP32Servo.h: Library for controlling servos using the ESP32.

AsyncTCP.h:

This library provides support for asynchronous TCP (Transmission Control Protocol) communications. Asynchronous communication allows the ESP32 to handle multiple connections and tasks simultaneously without blocking the main program execution. It's particularly useful for applications like web servers where the device needs to handle multiple client requests concurrently.
ESPAsyncWebServer.h:

This library allows you to create an asynchronous web server on the ESP32 microcontroller. It enables the ESP32 to serve web pages, handle HTTP requests, and interact with clients over the network. The asynchronous nature of this library ensures that the server can handle multiple requests simultaneously without blocking the execution of other tasks.
iostream and sstream:

These are standard C++ input/output stream libraries. They provide functionality for handling input and output operations in C++ programs. However, it's important to note that in embedded systems like the ESP32, the usage of C++ streams may be limited due to memory constraints. These libraries might be included for certain functionalities or debugging purposes.
ESP32Servo.h:

This library is used for controlling servos using the ESP32 microcontroller. Servos are commonly used in robotics and other projects where precise control of angular position is required. The ESP32Servo library provides functions to control the position and movement of servo motors connected to the ESP32's GPIO pins.