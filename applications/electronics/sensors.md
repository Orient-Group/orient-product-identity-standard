# 📡 Sensors

Smart sensors are foundational to home automation. They detect changes in the physical environment—such as motion, temperature, smoke, or water leakage—and communicate with control systems to trigger actions, alerts, or routines. These sensors play a critical role in ensuring security, safety, comfort, and energy efficiency in smart homes.

This nomenclature standard ensures a **uniform naming system** for all smart and non-smart sensors across product catalogs, packaging, apps, APIs, and control platforms like **Kontrol**. It enables easy categorization, compatibility tagging, and upgrade planning across multiple communication protocols (e.g., Zigbee, Wi-Fi, Bluetooth).

***

### 🧩 Format

> **Series + Quantifier + Design + Color \[+ Build Number]**

***

### 🔠 Series (Function)

Describes the **type of sensor**. One word only.

| Series  | Sensor Function                  |
| ------- | -------------------------------- |
| Motion  | Motion Sensor                    |
| Smoke   | Smoke Detector                   |
| Contact | Door/Window Contact Sensor       |
| Leak    | Water Leak Sensor                |
| Temp    | Temperature Sensor               |
| Humid   | Humidity Sensor                  |
| Gas     | Gas Detector                     |
| CO      | Carbon Monoxide Detector         |
| CO2     | Carbon Dioxide Detector          |
| Light   | Ambient Light Sensor             |
| Vibe    | Vibration Sensor                 |
| Multi   | Combo Sensor (e.g. Temp + Humid) |

***

### 🔢 Quantifier (1–4 Digit Cosmetic Code)

A 1 to 4-digit number for **cataloging, versioning, or aesthetic series placement**.\
No technical meaning—used purely for presentation.

| Examples | Interpretation          |
| -------- | ----------------------- |
| `1`      | Basic or first model    |
| `50`     | Advanced compact design |
| `300`    | Premium series          |
| `2025`   | Year-based edition      |

***

### 🎨 Design

Describes the **form factor or style** of the product. One word only.

| Examples |
| -------- |
| Mini     |
| Slim     |
| Cube     |
| Flat     |
| Disc     |
| Bar      |

***

### 🎨 Color

Describes the **primary product color**. One word only.

| Examples |
| -------- |
| White    |
| Black    |
| Grey     |
| Silver   |

***

### 🧱 Build Number

> **Major.Minor.Patch**

**🔹 Major – Smart/Non-Smart**

| Value | Meaning   |
| ----- | --------- |
| 0     | Non-Smart |
| 1     | Smart     |

***

**🔸 Minor – Smart Type (Protocol)**

| Value | Protocol  |
| ----- | --------- |
| 0     | None      |
| 1     | Wi-Fi     |
| 2     | Zigbee    |
| 3     | Bluetooth |
| 4     | Z-Wave    |
| 5     | Thread    |
| 6     | RF        |
| 7     | Dual      |
| 8     | PoE       |
| 9     | LoRa      |
| 10    | 4G        |

***

**🔹 Patch – Feature Set**

| Patch | Features Included                                                       |
| ----- | ----------------------------------------------------------------------- |
| 0     | Basic / Default                                                         |
| 1     | Battery-powered                                                         |
| 2     | Rechargeable battery                                                    |
| 3     | Tamper detection                                                        |
| 4     | LED alert                                                               |
| 5     | Sound/Buzzer alert                                                      |
| 6     | Cloud-sync enabled                                                      |
| 7     | OTA upgradable                                                          |
| 8     | External power supported                                                |
| 9     | IP-rated (e.g. waterproof)                                              |
| 10    | Combo features (for Multi series, e.g. Temp+Humid or Temp+Light+Motion) |

> Patch values represent bundled features; custom mappings per company catalog are allowed.

***

### 🧾 Examples

| Name                         | Meaning                                                   |
| ---------------------------- | --------------------------------------------------------- |
| Motion 1 Mini White 1.2.5    | Smart motion sensor, Zigbee, buzzer alert                 |
| Smoke 2025 Disc Black 1.1.3  | Smart smoke detector, Wi-Fi, tamper detection             |
| Contact 510 Slim White 0.0.0 | Non-smart door sensor, basic                              |
| Leak 20 Bar Grey 1.3.4       | Smart water leak sensor, Bluetooth, LED alert             |
| Multi 300 Cube White 1.2.10  | Smart combo sensor (e.g. Temp+Humid), Zigbee, combo patch |
