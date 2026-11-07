## Why I made this project
The main reason I'm making this project is because of cost. There are many many MMWave sensors out there. However, those that gives coordinates as to where a person is in the room often cost a lot of money.
Hence, I decided to build this project. This project only requires a microcontroller with WiFi capabilities so that it can talk to Home Assistant, as well as an LD2450, to detect mmWave presence.

## How it works
1. Through an ESPHome YAML, the YAML will be created and a fimrware can be flashed onto the ESP32
2. Upon ESP32 boot, Home Assistant will detect the ESP32 as a Device on the IoT Network
3. The Sensor will consistently broadcast information as to the whereabouts of where a person is in the room
## Main Components Used
1. Hi-Link LD2450
2. Esp32

## Wiring Digarm
<img width="1025" height="322" alt="Screenshot 2026-11-07 at 2 01 30 PM" src="https://github.com/user-attachments/assets/6be5f1fa-2d63-4a3e-9ba3-1f5a6eae9d5c" />

## 3D model renders
<img width="3040" height="1586" alt="96008ea5-9733-4368-9e97-135e732cbe4f" src="https://github.com/user-attachments/assets/dbf05ffb-5bb2-458b-9b1b-ff052d7c5e37" />
<img width="3040" height="1586" alt="8314888b-c149-41d6-be0a-52a5f6329e8b" src="https://github.com/user-attachments/assets/9c55a849-3778-4bdb-93fb-a2e48d068be9" />
<img width="3040" height="1586" alt="820df833-c6c7-4cdd-a9e6-b0def4637463" src="https://github.com/user-attachments/assets/39986553-7d66-4629-8a2c-18b04f90f9b1" />
