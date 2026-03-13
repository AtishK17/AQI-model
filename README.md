# IoT-Based Air Quality Monitoring System

An IoT-based real-time air quality monitoring system using **ESP8266 (NodeMCU)** and multiple gas sensors. The system measures environmental parameters and uploads them to **ThingSpeak Cloud** for remote monitoring.

---

## Features

- WiFi-enabled monitoring using ESP8266
- Temperature & Humidity measurement (DHT11)
- CO₂ & NH₃ estimation (MQ135)
- LPG & CH₄ detection (MQ2)
- Real-time cloud visualization using ThingSpeak
- Auto data upload every 15 seconds

---

## Hardware Used

- NodeMCU ESP8266
- DHT11 Temperature & Humidity Sensor
- MQ135 Air Quality Sensor
- MQ2 Gas Sensor
- Jumper Wires & Breadboard
- Power Supply (USB)

---

## Working Principle

1. ESP8266 connects to WiFi network.
2. Sensors collect environmental data.
3. Raw analog values are converted to approximate PPM values.
4. Data is uploaded to ThingSpeak Cloud.
5. Dashboard displays real-time graphs.

---

## ThingSpeak Fields

| Field | Parameter |
|-------|-----------|
| 1 | CO₂ (PPM) |
| 2 | NH₃ (PPM) |
| 3 | LPG (PPM) |
| 4 | CH₄ (PPM) |
| 5 | Temperature (°C) |
| 6 | Humidity (%) |

---

## Future Improvements

- Proper MQ sensor calibration using Rs/R0 method
- Add Buzzer for gas leakage alert
- Add OLED display for local monitoring
- Use external ADC for multiple analog inputs
- Deploy as industrial monitoring system

---

## Author

**Atish Kundu**
