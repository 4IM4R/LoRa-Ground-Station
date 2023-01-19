# LoRa Ground Station

Based on the project "Ground station for LoRa satellites" by alberto nunez https://hackaday.io/project/186243-ground-station-for-lora-satellites

Material:
  - TTGO LORA32 ESP32 with OLED
  - RP-SMA flange to U.FL pigtail
  - 433 Mhz antenna SMA
  - Generic 100x68x50mm waterproof enclosure box “Sonoff”
  - SMA Female To RP SMA Male adapter
  - Solar panel
  - 18650 3,7V battery
  - TP4056 battery charge manager
  - Female header 2.54mm
  - Screw terminal kf350 3.5mm 2 pin
  - MCP1700-3302E voltage regulator
  - 1uF electrolytic capacitor
  - 100nF film capacitor

Schematic:

https://github.com/4IM4R/LoRa-Ground-Station/blob/1a8263553356037dd365a862c32e084f3349d44a/images/Schematic.BMP?raw=true

Software:
  - TinyGS Firmware https://github.com/G4lile0/tinyGS
  - VSCode
  - Platformio

Installation guide:
  - Install VSCode https://code.visualstudio.com/download
  - Download repository (https://github.com/G4lile0/tinyGS) from Github. Code -> Download ZIP
  - Launch VSCode
  - Install Platformio in VSCode https://docs.platformio.org/en/latest/integration/ide/vscode.html
  - Upload project to TTGo https://github.com/G4lile0/tinyGS/wiki/Platformio
  
Configuration:
  - https://github.com/G4lile0/tinyGS/wiki/Ground-Station-configuration
  
