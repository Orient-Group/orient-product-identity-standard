# 📷 CCTV Cameras

### 🧩 About Product

Closed-Circuit Television (CCTV) cameras are essential for modern security, offering surveillance, deterrence, and real-time monitoring. The OPIS standard provides a consistent naming system for classifying all types of CCTV cameras by resolution, design, smart capability, and feature set. This structure simplifies cataloging, comparison, and system integration across both smart and non-smart product lines.

***

### 📊 Standard Format

> **\[Series Name] + \[Resolution] + \[Design] + \[Color] + \[Build Number]**

**Example:**\
`Guardian 4 Bullet White 1.1.4`

***

### 🏷️ Series Name

| Series   | Description                |
| -------- | -------------------------- |
| Eye      | Entry-level models         |
| Sentry   | Compact or indoor-focused  |
| Guardian | Rugged outdoor models      |
| Sentinel | Smart/AI-integrated models |
| Orb      | PTZ motorized cameras      |
| View360  | Fisheye panoramic cameras  |

***

### 📏 Resolution (Quantifier)

| Input | Description            |
| ----- | ---------------------- |
| 720p  | Entry-level HD         |
| 1080p | Full HD                |
| 2     | 2 Megapixel            |
| 4     | 4 Megapixel            |
| 5     | 5 Megapixel            |
| 8     | 8 Megapixel            |
| 4K    | Ultra HD (same as 8MP) |

> ✅ MP is the default unit. Only write suffix for **720p**, **1080p**, or **4K**.

***

### 🧱 Design

| Design  | Description                     |
| ------- | ------------------------------- |
| Dome    | Ceiling-mounted                 |
| Bullet  | Outdoor cylindrical body        |
| Turret  | Flexible dome-like adjustment   |
| PTZ     | Pan-Tilt-Zoom motorized         |
| Cube    | Small form indoor camera        |
| Fisheye | 180° or 360° panoramic coverage |

***

### 🎨 Color

| Color    |
| -------- |
| White    |
| Black    |
| Grey     |
| Dualtone |

***

### 🔢 Build Number

> **\[Major].\[Minor].\[Patch]**

***

#### 🔹 Major – Smart Category

| Value | Description |
| ----- | ----------- |
| 0     | Non-Smart   |
| 1     | Smart       |

***

#### 🔸 Minor – Smart Type

| Value | Smart Type                      |
| ----- | ------------------------------- |
| 0     | None (used with Non-Smart only) |
| 1     | Wi-Fi                           |
| 2     | PoE (Ethernet)                  |
| 3     | 4G                              |
| 4     | Dual (Wi-Fi + PoE)              |
| 5     | Matter                          |

> ✅ When **Major = 0 (Non-Smart)**, **Minor must = 0 (None)**.

***

#### 🔻 Patch – Features (Lens, AI, Storage)

| Value | Feature Set Description                               |
| ----- | ----------------------------------------------------- |
| 0     | Basic lens, no night vision, no AI, SD/NVR only       |
| 1     | IR Night Vision + Human Detection + Cloud             |
| 2     | Full-Color Night Vision + Face Recognition + NVR      |
| 3     | Motorized Zoom + IR + LPR + NVR                       |
| 4     | Full-Color Night Vision + LPR + Motion Zones          |
| 5     | PTZ + Full AI Suite (Face, Object, LPR) + NVR + Cloud |

***

### ✅ Examples

| Full Name                       | Build | Explanation                                  |
| ------------------------------- | ----- | -------------------------------------------- |
| `Eye 720p Dome White 0.0.0`     | 0.0.0 | Non-smart, no smart type, basic lens         |
| `Sentry 1080p Cube Black 1.1.1` | 1.1.1 | Smart Wi-Fi, IR + Human Detection + Cloud    |
| `Guardian 4 Bullet White 1.2.4` | 1.2.4 | Smart PoE, Color Night Vision + LPR + Zones  |
| `Sentinel 5 Turret Grey 1.1.2`  | 1.1.2 | Smart Wi-Fi, Color Night Vision + Face + NVR |
| `Orb 4K PTZ White 1.2.5`        | 1.2.5 | Smart PoE, PTZ + Full AI + Hybrid Storage    |
