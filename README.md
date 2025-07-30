# Resource Conscious AC Enhancement System
• Created an IoT-based device to remotely control non-smart ACs, automating temperature and humidity using LM35 and DHT22 sensors. • Integrated a water recycling system to reuse AC drainage for room humidification. • Enabled occupancy-based control using LD-2410 to switch off ACs when no one is present.

**Update #1**

Components required:

1. ESP-32 Microcontroller board
2. HLK-LD2410 24Ghz Occupancy and presence detection Sensor
3. PM2.5 GP2Y1010AU0F Dust Smoke Particle Sensor
4. AHT-20 Temperature and Humidity Sensor
5. Super Ultrasonic Mist Maker Humidifier
6. 38KHz Infrared Transmit Sensor Module and Infrared IR Sensor Receiver Module for Arduino

**Update #2**

**• Methodology:**

• Data Collection: Sensors (Temp, Humidity, Motion) continuously monitor room conditions.
• Prediction: ESP32 uses algorithm to predict optimal temperature settings based on historical data & real-time environmental factors.
• Automation: Microcontroller (ESP32) automates AC operation via relays.
• Energy Savings: System adjusts cooling based on occupancy, avoiding energy waste.

**Statistics**

● A 1 ton air conditioner can produce up to 10 liters of water in 7-8 hours.
● A dirty AC filter can increase the power consumption of an air conditioner by 5% to 15%. For
  example, if an AC typically consumes 1,000 watts (1 kW), a dirty filter could cause it to use
  an additional 50 to 150 watts, depending on how clogged the filter is.
● In the Indian market, the price difference between a non-smart AC (less efficient) and a
  smart AC(more efficient) typically ranges from ₹10,000 to ₹15,000.
