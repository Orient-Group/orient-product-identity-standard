# 🪟 Curtain Controllers

### 🧩 About Product

Curtain controllers are motorized systems used to open and close curtains or blinds automatically. These devices may support wall switches, remote control, or smart integration (Wi-Fi, Zigbee, etc.) for automation. Common variations include single vs. dual track, retrofit kits, and integration with voice assistants or mobile apps.

***

### 📊 Standard Format

> **Series + Quantifier + Design + Color \[+ Build Number]**

Example:\
`Glide 25 Slim White 1.1.3`

***

### 🏷️ Series

| Name  | Description                                |
| ----- | ------------------------------------------ |
| Glide | Standard motorized curtain controller      |
| Fold  | Designed for roman/foldable blinds         |
| Retro | Retrofit motor for existing curtain tracks |
| Dual  | Dual-motor or dual-track support           |
| Multi | Multi-channel curtain control (3+ tracks)  |

***

### 🔢 Quantifier

Describes capacity or model marker, depending on product type.

| Value | Meaning                     |
| ----- | --------------------------- |
| 25    | 25W motor power             |
| 45    | 4.5m track length supported |
| 2025  | Launch year or series year  |

***

### 🎨 Design

| Value | Description                       |
| ----- | --------------------------------- |
| Slim  | Compact vertical profile          |
| Boxy  | Rectangular or embedded design    |
| Bar   | Horizontal bar-type motor unit    |
| Rail  | Built-in motor with curtain track |

***

### 🎨 Color

Common standard options:

* White
* Black
* Grey
* Silver

***

### 🛠️ Build Number

> Format: `Major.Minor.Patch`\
> Encodes Smart Capability, Smart Type, and Feature Set.

***

#### 🔹 Major – Smart / Non-Smart

| Value | Meaning   |
| ----- | --------- |
| 0     | Non-Smart |
| 1     | Smart     |

***

#### 🔹 Minor – Smart Type

| Value | Meaning   |
| ----- | --------- |
| 0     | None      |
| 1     | Wi-Fi     |
| 2     | Zigbee    |
| 3     | Bluetooth |
| 4     | RF        |
| 5     | Z-Wave    |
| 6     | Matter    |

***

#### 🔹 Patch – Feature Set

| Value | Included Features                                              |
| ----- | -------------------------------------------------------------- |
| 0     | Basic motor, single track                                      |
| 1     | Dual track support                                             |
| 2     | Battery backup                                                 |
| 3     | Voice assistant integration (Alexa, Google)                    |
| 4     | Curved track support                                           |
| 5     | Adjustable torque                                              |
| 6     | Retrofit compatibility                                         |
| 7     | App + voice + schedule automation                              |
| 8     | Remote control + limit switch calibration                      |
| 9     | Full feature pack: dual track + curved + voice + app + battery |

***

### 🧪 Recipe (Optional, for Smart Models)

Defines supported protocols, platforms, and control interfaces.

**Example Recipe:**\
`Wi-Fi, App Control, Google Assistant, Alexa, Schedule Automation`

***

### 🧾 Examples

| Name                       | Meaning                                                           |
| -------------------------- | ----------------------------------------------------------------- |
| Glide 25 Slim White 0.0.0  | Non-smart, 25W motor, compact design                              |
| Fold 2025 Boxy Black 1.1.3 | Smart (Wi-Fi), supports voice, boxy design, launched 2025         |
| Retro 45 Rail Grey 0.0.6   | Non-smart retrofit motor for up to 4.5m rail, retrofit compatible |
| Dual 35 Bar Silver 1.2.9   | Zigbee-based dual track controller with full feature pack         |
