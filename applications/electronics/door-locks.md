# 🔒 Door Locks

### 🧩 About Product

Door locks are essential security devices used in residential, commercial, and industrial spaces. They may be **mechanical** (non-smart) or **smart**, incorporating features such as fingerprint recognition, PIN/keypad access, RFID cards, app control, and remote unlocking. This standard enables consistent product naming across both smart and non-smart categories.

***

### 📊 Standard Format

> **Series + Quantifier + Design + Color \[ + Build Number ]**

***

### 🏷️ Series

Brand-defined line or theme (e.g., Fortis, Nova, Titan, Guardian). Must be a single word.

***

### 🔢 Quantifier

A **cosmetic identifier** used for cataloging or marketing purposes.\
It **does not carry technical meaning**.

**Allowed formats:**

* **Year**: e.g., `2023`
* **Generation**: e.g., `2G`, `3G`
* **SKU**: e.g., `504`, `X1`

***

### 🎨 Design

The physical or stylistic identity of the lock. Must be a **one-word descriptor**.

**Examples:** `Slim`, `Classic`, `Bold`, `Mini`, `Rugged`

***

### 🎨 Color

The lock’s outer finish. Standard one-word color names like:

**Examples:** `Black`, `Silver`, `Champagne`, `Bronze`

***

### 🏗️ Build Number

> **Major.Minor.Patch**

| Component | Definition  |
| --------- | ----------- |
| **Major** | Smart Type  |
| **Minor** | Lock Type   |
| **Patch** | Feature Set |

***

#### 🔹 Major – Smart Type

| Code | Type      |
| ---- | --------- |
| 0    | Non-Smart |
| 1    | Smart     |

***

#### 🔹 Minor – Lock Type

| Code | Lock Type            |
| ---- | -------------------- |
| 0    | Generic Mechanical   |
| 1    | Deadbolt             |
| 2    | Mortise              |
| 3    | Glass Door           |
| 4    | Cabinet              |
| 5    | Padlock              |
| 6    | Sliding Door         |
| 7    | Hotel RFID/Card Lock |
| 8    | Gate Lock            |

***

#### 🔹 Patch – Feature Set

| Code | Features                                                    |
| ---- | ----------------------------------------------------------- |
| 0    | Basic                                                       |
| 1    | Fingerprint                                                 |
| 2    | Keypad / PIN                                                |
| 3    | Card / RFID                                                 |
| 4    | App Control (Bluetooth/Wi-Fi)                               |
| 5    | Auto Lock / Remote Unlock                                   |
| 6    | Guest Access / OTP                                          |
| 7    | Battery Backup                                              |
| 8    | Alarm / Tamper Alert                                        |
| 9    | Log History / Access Records                                |
| 10   | Voice Assistant Integration                                 |
| 11   | All-in-One (Biometric + PIN + App + Logs + Auto Lock, etc.) |

***

### 🧪 Examples

| Name                             | Meaning                                  |
| -------------------------------- | ---------------------------------------- |
| Fortis 2023 Classic Bronze 0.1.0 | Non-smart deadbolt lock (2023 model)     |
| Nova 2G Slim Black 1.1.1         | Smart deadbolt with fingerprint          |
| Guardian 4G Bold Silver 1.2.11   | Smart mortise lock with full feature set |
| Vault 305 Slim MatteGold 0.3.0   | Non-smart glass door lock                |
| Titan 504 Rugged Black 1.5.4     | Smart padlock with app control           |
| Vibe 309 Mini White 1.4.3        | Smart cabinet lock with RFID/card access |

