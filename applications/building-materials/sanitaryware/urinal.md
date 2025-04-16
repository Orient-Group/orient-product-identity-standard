# 🚹 Urinal

### 🧩 About Product

Orient urinals are designed for hygienic, space-efficient male washroom installations. They come in various designs including **compact**, **twin-set**, and **wall-mounted**, and may support manual or automatic flushing mechanisms. The OPIS naming system ensures each urinal is presented in a structured, understandable, and searchable format across packaging, catalogs, and backend systems.

***

### 📊 Standard Format

> **Series Name + Size + Design + Color \[+ Build Number]**

* The first four parts are the **customer-visible product name**
* The **Build Number** is used internally for configuration and tracking

***

### 🏷️ Series Name

Identifies the urinal’s visual family or product line.\
Must be a **real English word**, max 8 characters.

**Examples:** Core, Glide, Swift, Nova, Bold, Axis

***

#### 📏 Quantifier (Size)

The quantifier reflects the **urinal height and width**, in cm:

> **Height x Width**

**Examples:**

* 55x35
* 60x38
* 65x40

> This format ensures clarity in installation space planning. “cm” is not shown in the name.

***

### 🖌️ Design

The **aesthetic identity** or visual styling of the urinal.\
Must be a real English word (max 8 characters).

**Examples:**\
Edge, Arc, Shell, Rise, Slate, Line

> Cannot describe the type (e.g., “Wall”, “Compact”) — those belong in the build number.

***

### 🎨 Color

The body color of the ceramic. Must be a single English word, max 8 characters.

**Approved Colors:**\
White, Ivory, Grey, Sand, Cream, Biscuit, Almond, Black

***

### 🔢 Build Number (Internal Use Only)

Tracks installation style, flushing type, and extra features.

> **Format:** `Major.Minor.Recipe`

**Major – Urinal Type**

| Type          | Code |
| ------------- | ---- |
| Wall-Mounted  | 1    |
| Floor-Mounted | 2    |
| Twin          | 3    |
| Sensor Urinal | 4    |

**Minor – Flushing System**

| System            | Code |
| ----------------- | ---- |
| Manual Flush      | 1    |
| Integrated Sensor | 2    |
| Concealed Cistern | 3    |

**Recipe – Optional Features**

| Feature              | Code |
| -------------------- | ---- |
| Standard             | 0    |
| Anti-Splash Rim      | 1    |
| Water Saving Mode    | 2    |
| Odor Trap (Built-in) | 3    |

***

### ✅ Example Breakdown

<table><thead><tr><th width="215.25390625">Product Name</th><th width="73.66796875">Build</th><th>Explanation</th></tr></thead><tbody><tr><td>Nova 60x38 Edge White</td><td>–</td><td>White urinal, 60x38 cm, design “Edge”</td></tr><tr><td>Core 55x35 Arc Ivory</td><td>1.1.0</td><td>Wall-mounted, manual flush, standard</td></tr><tr><td>Glide 65x40 Shell Grey</td><td>3.3.1</td><td>Twin floor-mounted urinal with concealed flush and anti-splash rim</td></tr><tr><td>Swift 60x38 Rise White</td><td>4.2.2</td><td>Sensor urinal, integrated flush, with water-saving feature</td></tr></tbody></table>
