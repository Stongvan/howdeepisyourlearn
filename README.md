# howdeepisyourlearn
# SmartBin: AI-Driven Food Waste Reduction for Singapore

**2023 National Sustainability Hackathon Submission**

## Features
1. Real-time food waste classification (YOLOv8 + U-Net)
2. Cost analysis using SFA price data
3. Carbon footprint tracking (NEA-compliant)
4. IoT-integrated ordering system

## Hardware Requirements
- Raspberry Pi 4 + Camera Module v2
- Arduino Uno + Load Cell (HX711)
- Singapore 230V Power Supply

## Setup
1. **Flash Arduino**:
   ```bash
   arduino-cli compile --fqbn arduino:avr:uno scale_sensor.ino
