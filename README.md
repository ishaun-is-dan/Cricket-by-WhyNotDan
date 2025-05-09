cricket by WhyNotDan ESP32-based project that creates a local web interface to control an active buzzer with three distinct sound modes. The system establishes its own WiFi network (SoftAP) and provides a responsive web interface for controlling the buzzer.

Features
Three Sound Modes:
🦗 Cricket Sound (adjustable chirp interval)
🔊 Normal Buzzer (continuous sound)
⏲️ Beeping Sound (adjustable beep interval)

Web Interface:
Clean, mobile-friendly design
Toggle switches for each sound mode
Interval adjustment controls (0.5s, 1s, 2s, 3s)
Real-time feedback

Technical Specifications:
ESP32 microcontroller
Active buzzer connected to GPIO 34
SoftAP WiFi network (no external WiFi required)

Hardware Requirements:
ESP32 development board
Active buzzer (5V compatible)
Breadboard and jumper wires
Micro USB cable for power/programming

Wiring Diagram:
ESP32 GPIO4 ────(+) Buzzer
ESP32 GND    ────(-) Buzzer
