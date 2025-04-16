# 🚿 Bidet

### 🧩 About Product

Orient bidets offer a hygienic and comfortable washing experience as part of modern bathroom solutions. These are typically floor-mounted ceramic units, available in both standard and smart variants. The OPIS structure ensures consistency in how each bidet is named, labeled, and systemized across all product platforms.

***

### 📊 Standard Format

> **Series Name + Size + Design + Color \[+ Build Number]**

* The first four elements form the **public product name**
* The optional **Build Number** is used for internal classification and system control

***

### 🏷️ Series Name

Defines the visual family or product line of the bidet.\
Must be a **real English word**, with a max of 8 characters.

**Examples:** Aura, Nova, Bold, Curve, Grace, Swan

***

### 📏 Quantifier (Size)

Bidets are quantified using their **Width x Depth** (in cm):

> **Width x Depth**

**Examples:**

* 36x56
* 38x58
* 40x60

> This provides useful size reference for bathroom layout planning.

***

### 🖌️ Design

Describes the **visual design language** of the bidet — not its technical form.\
Must be a **real English word**, max 8 characters.

**Examples:**\
Grace, Curve, Arc, Zen, Edge, Shell

> Mounting type or function (e.g., “Wall”, “Smart”) is **not** allowed in this field.

***

### 🎨 Color

Visible ceramic color. Must be a real English word, single word, max 8 characters.

**Approved Colors:**\
White, Ivory, Grey, Sand, Cream, Biscuit, Almond, Black

***

### 🔢 Build Number (Internal Use Only)

Tracks **type**, **flush/water supply method**, and **feature set**.

> **Format:** `Major.Minor.Recipe`

**Major – Bidet Type**

| Type          | Code |
| ------------- | ---- |
| Floor-Mounted | 1    |
| Wall-Hung     | 2    |
| Smart Bidet   | 3    |

**Minor – Water Supply Type**

| Supply System     | Code |
| ----------------- | ---- |
| Manual Faucet     | 1    |
| Integrated Jet    | 2    |
| Sensor-Controlled | 3    |

**Recipe – Features**

| Feature                | Code |
| ---------------------- | ---- |
| Standard               | 0    |
| Soft Close Lid         | 1    |
| EcoFlush               | 2    |
| Heated Seat (Smart)    | 3    |
| Smart Controls (Touch) | 4    |

***

### ✅ Example Breakdown

<table><thead><tr><th width="217.65234375">Product Name</th><th width="67.453125">Build</th><th>Explanation</th></tr></thead><tbody><tr><td>Aura 36x56 Grace White</td><td>–</td><td>White floor-mounted bidet, 36x56 cm, design “Grace”</td></tr><tr><td>Nova 38x58 Zen Ivory</td><td>1.2.0</td><td>Floor-mounted with integrated water jet, no extra features</td></tr><tr><td>Curve 40x60 Edge Grey</td><td>3.3.4</td><td>Smart bidet, sensor water supply, smart control touch panel</td></tr><tr><td>Swan 36x56 Arc White</td><td>2.1.1</td><td>Wall-hung with manual faucet, soft close lid</td></tr></tbody></table>
