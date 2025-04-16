# 🚰 Cistern

### 🧩 About Product

Orient cisterns are compact ceramic or plastic water tanks used to control flushing in toilets. They may be mounted on the wall or integrated with WCs. Cisterns vary by flush type (single, dual), visibility (exposed/concealed), and add-on features (soft button, smart sensor). OPIS naming ensures that these variations are captured in a simple, structured, and customer-friendly naming format.

***

### 📊 Standard Format

> **Series Name + Size + Design + Color \[+ Build Number]**

* First four fields are part of the **human-readable name**
* **Build Number** is used internally for system configuration

***

### 🏷️ Series Name

Refers to the product line or visual identity of the cistern.\
Must be a **real English word**, max 8 characters.

**Examples:** Core, Nova, Axis, Swift, Bold

***

### 📏 Quantifier (Size)

Quantifier refers to the **tank volume in liters**:

> Numeric value only — no “L” in name

**Examples:**

* 6
* 9
* 10

> The actual capacity (e.g., 6L) will be documented, but only the numeric value appears in the product name.

***

### 🖌️ Design

Visual or aesthetic styling of the unit. Not a functional descriptor.\
Must be a real English word (max 8 characters).

**Examples:**\
Slate, Rise, Shell, Edge, Line, Block

> Cannot use words like “Wall” or “Dual” in this field.

***

### 🎨 Color

Specifies the outer casing color.\
Must be a single English word, max 8 characters.

**Approved Colors:**\
White, Ivory, Grey, Sand, Cream, Biscuit, Almond, Black

***

### 🔢 Build Number (Internal Use Only)

Tracks mounting type, flushing system, and special features.

> **Format:** `Major.Minor.Recipe`

**Major – Mounting Type**

|                           |          |
| ------------------------- | -------- |
| **Mount Type**            | **Code** |
| Wall-Mounted              | 1        |
| Concealed/In-Wall         | 2        |
| Integrated (One-Piece WC) | 3        |

**Minor – Flushing System**

|                |          |
| -------------- | -------- |
| **Flush Type** | **Code** |
| Single Flush   | 1        |
| Dual Flush     | 2        |
| Sensor Flush   | 3        |

**Recipe – Features**

|                   |          |
| ----------------- | -------- |
| **Feature**       | **Code** |
| Standard          | 0        |
| Soft Touch Button | 1        |
| Chrome Button     | 2        |
| Smart Flush Delay | 3        |
| Water-Saving Mode | 4        |

***

### ✅ Example Breakdown

| Product Name        | Build | Explanation                                                 |
| ------------------- | ----- | ----------------------------------------------------------- |
| Core 6 Shell White  | –     | 6L cistern in white, design “Shell”, from Core series       |
| Nova 9 Block Ivory  | 1.2.0 | Wall-mounted cistern, dual flush, standard button           |
| Swift 10 Slate Grey | 2.3.3 | Concealed cistern with sensor flush and smart delay feature |
| Axis 6 Rise White   | 1.1.2 | Wall-mounted, single flush with chrome button               |
