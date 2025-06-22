# 🧠 Control Panels & Gateways

### 🧩 About Product

Control Panels are centralized devices used to operate, monitor, or coordinate smart environments such as homes, offices, or buildings. These may include:

* **Touchscreen Panels** (wall/table/handheld)
* **Remotes** (IR/RF/Bluetooth)
* **Gateways** (e.g., Zigbee, Matter, Thread hubs)
* **Relay Boxes** (for load control)

They differ in form factor, intelligence, and supported protocols.

***

### 📊 Standard Format

> **Series Name + Quantifier + Design + Color \[+ Build Number]**

***

### 🏷️ Series Name

Max 8 characters. Should reflect the visual/functional family.

| Theme              | Examples                |
| ------------------ | ----------------------- |
| Intelligence       | Core, Neo, Logic, Link  |
| Futurism           | Pulse, Nova, Edge, Halo |
| Minimal Aesthetics | Arc, Frame, Glide, Aura |

***

### 📏 Quantifier

Refers strictly to **screen size** in inches.

| Value | Meaning                                                   |
| ----- | --------------------------------------------------------- |
| `7`   | 7-inch screen panel                                       |
| `10`  | 10-inch screen panel                                      |
| `4`   | 4-inch screen panel                                       |
| `0`   | **Headless device** (e.g., gateways, remotes, relay hubs) |

***

### 🖌️ Design

Describes the industrial design (not functionality).

**Examples:** Flat, Bezel, Box, Stick, Curved, Classic

***

### 🎨 Color

Standardized color name (≤ 8 characters)

**Examples:** White, Black, Grey, Silver, Gold

***

### 🔢 Build Number

Format: **Major.Minor.Recipe**

***

#### ✅ Major – OS / Core Logic

| Code | Type            |
| ---- | --------------- |
| 1    | Android         |
| 2    | Linux           |
| 3    | RTOS            |
| 4    | Custom Embedded |
| 5    | No OS / Relay   |

***

#### ✅ Minor – Form Factor

| Code | Form Factor              |
| ---- | ------------------------ |
| 0    | Wall-Mounted Panel       |
| 1    | Handheld Remote          |
| 2    | Tabletop Unit            |
| 3    | Box Controller / Gateway |
| 4    | Rack-Mount Unit          |

***

#### ✅ Recipe – Protocols & Features

| Code | Description                 |
| ---- | --------------------------- |
| 0    | None (basic)                |
| 1    | Wi-Fi                       |
| 2    | Zigbee                      |
| 3    | Matter                      |
| 4    | Wi-Fi + Zigbee              |
| 5    | Wi-Fi + Zigbee + Matter     |
| 6    | Google Assistant            |
| 7    | Amazon Alexa                |
| 8    | Energy Monitoring           |
| 9    | Scene Control Support       |
| A    | Video Feed / Camera Support |
| B    | BLE + Thread                |
| C    | RF + IR Blaster             |
| D    | Relay Triggering            |
| E    | API/Cloud Integration       |

***

### 💡 Example Names

| Product Name         | Build No. | Description                                      |
| -------------------- | --------- | ------------------------------------------------ |
| Core 7 Flat White    | 1.0.4     | Android wall panel, 7", Wi-Fi + Zigbee           |
| Neo 10 Bezel Black   | 2.0.5     | Linux wall panel, 10", Wi-Fi + Zigbee + Matter   |
| Nova 0 Box Black     | 2.3.5     | Linux headless gateway, box-style, all protocols |
| Aura 4 Curved Silver | 1.0.6     | Android 4" panel, Google Assistant               |
| Link 0 Box Grey      | 5.3.D     | Relay box, headless, relay triggering capable    |
| Halo 0 Stick Black   | 4.1.C     | Embedded remote, RF + IR                         |
