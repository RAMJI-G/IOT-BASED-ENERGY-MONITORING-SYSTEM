# ⚡ IoT Based Energy Monitoring System (EMS)

An advanced IoT-based Smart Energy Monitoring System developed using ESP8266, ACS712, ZMPT101B, OLED Display, Blynk IoT, and Embedded Systems concepts.

The system monitors:

- Voltage (V)
- Current (A)
- Power (W)

in real time and displays the values on an OLED screen while also sending data to the Blynk IoT cloud platform for wireless monitoring.

---

# 🚀 Features

✅ Real-Time Voltage Monitoring  
✅ Real-Time Current Monitoring  
✅ Real-Time Power Monitoring  
✅ OLED Live Display  
✅ Blynk IoT Cloud Integration  
✅ SuperChart Graph Visualization  
✅ Smart Filtering Algorithm  
✅ Noise Reduction  
✅ Stable Power Calculation  
✅ Professional OLED UI  
✅ Startup Animation  
✅ Startup Buzzer Alert  
✅ Single A0 Smart Sensor Switching  
✅ WiFi-Based Monitoring  
✅ Embedded Systems + IoT Project  

---

# 🧠 Technologies Used

- ESP8266 NodeMCU
- Embedded Systems
- Internet of Things (IoT)
- Arduino IDE
- Blynk IoT
- OLED SSD1306
- ACS712 Current Sensor
- ZMPT101B Voltage Sensor
- WiFi Communication

---

# 🔩 Components Used

| Component | Quantity |
|---|---|
| ESP8266 NodeMCU | 1 |
| ACS712 Current Sensor | 1 |
| ZMPT101B Voltage Sensor | 1 |
| OLED SSD1306 Display | 1 |
| SPDT Switch | 1 |
| Buzzer | 1 |
| Bulb Holder | 1 |
| 9W AC LED Bulb | 1 |
| Breadboard | 1 |
| Jumper Wires | Multiple |

---

# 🔌 Circuit Connections

## OLED Display

| OLED Pin | ESP8266 |
|---|---|
| VCC | 3.3V |
| GND | GND |
| SDA | D2 |
| SCL | D1 |

---

## Buzzer

| Buzzer Pin | ESP8266 |
|---|---|
| + | D5 |
| - | GND |

---

## SPDT Switch

| SPDT Pin | Connection |
|---|---|
| Center | A0 |
| Left | ACS712 OUT |
| Right | ZMPT101B OUT |

---

# ⚙️ Working Principle

1. ACS712 measures current.
2. ZMPT101B measures voltage.
3. SPDT switch selects sensor output to A0.
4. ESP8266 processes sensor values.
5. Smart filtering improves stability.
6. OLED displays:
   - Voltage
   - Current
   - Power
7. Blynk receives live IoT data.
8. Power is calculated using:

```text
Power = Voltage × Current
```

---

# 📟 OLED Output

```text
SMART EMS
----------------

MODE: VOLTAGE

VOLTAGE: 229.4V
CURRENT: 0.04A
POWER  : 10.3W
```

---

# 📱 Blynk Dashboard

The Blynk IoT dashboard displays:

- Voltage Gauge
- Current Gauge
- Power Gauge
- SuperChart Graph
- Online Monitoring

---

# 📊 Expected Values (9W Bulb)

| Parameter | Expected Range |
|---|---|
| Voltage | 220V – 240V |
| Current | 0.04A – 0.05A |
| Power | 8W – 12W |

---

# 🌍 Applications

- Smart Homes
- Energy Monitoring Systems
- Smart Electrical Labs
- IoT Learning Projects
- Embedded Systems Projects
- Smart Automation Systems
- Power Consumption Analysis

---

# ✅ Advantages

- Low Cost
- Wireless Monitoring
- Real-Time Analytics
- Compact Design
- Professional OLED Interface
- IoT Cloud Support
- Stable Readings
- Smart Filtering System

---

# 🔮 Future Improvements

- Mobile Notifications
- Relay Automation
- Google Assistant Integration
- Smart Home Expansion
- AI-Based Analytics
- Overload Protection
- Data Logging
- MQTT Integration

---

# 🧪 Project Type

Embedded Systems + IoT + Smart Monitoring

---

# ⭐ Project Status

✅ Completed  
✅ Working Prototype  
✅ IoT Enabled  
✅ Portfolio Ready  
✅ Engineering Mini Project  
✅ Competition Ready
