# ESP32 Web Server


## Description
This project demonstrates how to create a web server using an ESP32 microcontroller. The web server can be used to control LEDs connected to the ESP32 via a web interface. It serves a simple HTML page with buttons to turn LEDs on and off.

## Features
- Control LEDs via a web interface
- Serve HTML content from the ESP32
- Handle multiple clients

## Getting Started

### Prerequisites
- ESP32 development board
- Arduino IDE or PlatformIO
- USB cable to connect ESP32 to your computer

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/fguzman82/esp32-webserver.git
    cd esp32-webserver
    ```

2. Open the project in your development environment (Arduino IDE or PlatformIO).

3. Install the necessary libraries:
    - WiFi
    - WebServer

### Usage
1. Connect the ESP32 to your computer using a USB cable.

2. Open the `esp32-webserver.ino` file in your development environment.

3. Modify the WiFi credentials:
    ```cpp
    const char* ssid = "your_SSID";
    const char* password = "your_PASSWORD";
    ```

4. Upload the code to your ESP32.

5. Open the Serial Monitor to find the IP address of your ESP32.

6. Open a web browser and enter the IP address to access the web server.

