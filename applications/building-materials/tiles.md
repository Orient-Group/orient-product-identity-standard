# ❇️ Tiles

### 🧩 About Product

Orient tiles are used in both **flooring and wall applications**, across interior and exterior spaces. The range includes a variety of **formats**, **design themes**, **surfaces**, and **materials** such as porcelain and ceramic. The goal of the OPIS structure is to present tile products in a way that is simple to read, easy to recall, and consistent across all systems.

***

### 📊 Standard Format

> **Series + Size + Surface + Color \[+ Build Number]**

* The first four elements form the **human-readable product name**
* The **Build Number** is optional and used for **internal specification tracking**

***

### 🏷️ Series

Represents the **design collection** or **visual theme** of the tile. It is typically unique and ownable for brand differentiation.

* Must be a real English word or phonetically easy coined word
* Max 8 characters

**Examples:** Karakor, Roman, Ridge, Spark, Slate, Luxor, Nova, Orion

***

### 📏 Quantifier (Size)

Indicates the **dimensions** of the tile in centimeters. Format must be **width x height**.

**Examples:**

* 30x60
* 60x60
* 60x120

> Units (cm) are not written in the name but documented internally

🔸 For **multi-tile portrait sets**, a **letter suffix (A, B, C, etc.)** is added directly after the size to denote tile order within the mural.

**Examples:**

* Orion 30x60A Marble Beige
* Orion 30x60B Marble Beige
* Orion 30x60C Marble Beige

***

### 🧱 Surface

Refers to the **visual texture or design finish** of the tile.

| Surface Type | Description                                     |
| ------------ | ----------------------------------------------- |
| Marble       | Classic veined finish resembling natural marble |
| Stone        | Textured to resemble natural stones             |
| Concrete     | Industrial cement-like matte finish             |
| Wood         | Printed wooden grain, plank-like aesthetics     |
| Metal        | Sleek or brushed metallic finish                |
| Solid        | Plain surface, no visible grain or design       |
| 3D           | Raised or embossed visual depth pattern         |

> Must be selected from this **approved list only**\
> Capitalized and restricted to a single word

***

### 🎨 Color

Specifies the **primary color** of the design. Each color must be a **real English word**, max 8 characters.

**Approved Colors:**\
Aqua, Ash, Beige, Biscoti, Black, Bone, Bronze, Brown, Camel, Caramel, Cement, Charcoal, Clay, Cocoa, Ginger, Gold, Graphite, Green, Greige, Grey, Ivory, Olive, Orange, Pearl, Rust, Sepia, Silver, White

***

### 🔢 Build Number (Internal Use Only)

The **Build Number** provides detailed classification of technical specifications including body material, finish type, and specialty coating. It is used strictly for internal version control and system traceability.

> **Format:** `Major.Minor.Recipe`

| Component  | Represents                 |
| ---------- | -------------------------- |
| **Major**  | Body Type (Material)       |
| **Minor**  | Finish Type (Matte/Polish) |
| **Recipe** | Specialty Coating/Effect   |

#### 🧮 Build Number Reference Table

**Major – Body Type**

| Type      | Code |
| --------- | ---- |
| Porcelain | 1    |
| Ceramic   | 2    |

**Minor – Finish Type**

| Finish | Code |
| ------ | ---- |
| Matte  | 1    |
| Polish | 2    |

**Recipe – Specialty Surface / Effects**

<table><thead><tr><th width="86.53125">Code</th><th>Recipe Name</th></tr></thead><tbody><tr><td>1</td><td>Super Matte</td></tr><tr><td>2</td><td>Super Matte + Rocker &#x26; Lustre</td></tr><tr><td>3</td><td>Velvet</td></tr><tr><td>4</td><td>Velvet + Rocker &#x26; Lustre</td></tr><tr><td>5</td><td>Diamond Matte</td></tr><tr><td>6</td><td>Anti Slip</td></tr><tr><td>7</td><td>Grit Basic</td></tr><tr><td>8</td><td>Grit Pro Max</td></tr><tr><td>9</td><td>Pantone Matte</td></tr><tr><td>10</td><td>3D</td></tr><tr><td>11</td><td>3D + Lustre</td></tr><tr><td>12</td><td>3D Deep</td></tr><tr><td>13</td><td>Super Shine</td></tr><tr><td>14</td><td>Zero Shine</td></tr><tr><td>15</td><td>Structure Shine</td></tr><tr><td>16</td><td>Diamond Shine</td></tr><tr><td>17</td><td>Pantone Shine</td></tr></tbody></table>

***

### ✅ Example Breakdown

<table><thead><tr><th width="283.2265625">Product Name</th><th>Explanation</th></tr></thead><tbody><tr><td>Karakor 60x120 Marble White</td><td>White marble-look porcelain tile in 60x120 size</td></tr><tr><td>Roman 60x60 Stone Grey</td><td>Grey stone-style ceramic tile, 60x60 size</td></tr><tr><td>Ridge 30x60 Concrete Ash 1.1.1</td><td>Porcelain, matte base, Super Matte finish</td></tr><tr><td>Slate 60x60 3D Black 2.2.11</td><td>Ceramic, polished tile with 3D + Lustre coating</td></tr><tr><td>Orion 30x60A Marble Beige</td><td>First tile in a multi-piece portrait mural (Tile A of set)</td></tr><tr><td>Orion 30x60B Marble Beige</td><td>Second tile in same mural set (Tile B of set)</td></tr></tbody></table>

***

### 💡 Backwards Compatibility

| Old Name                               | New Name                     |
| -------------------------------------- | ---------------------------- |
| FL MARMI ORION SS 600X1200 WT L        | Orion 60x120 Marble White    |
| TL SLATE KHAKI 3D LT 600X1200 L        | Slate 60x120 3D Khaki        |
| TL SLATE IVORY 3D LT 600X1200 L        | Slate 60x120 3D Ivory        |
| TL SLATE ASH 3D LT 600X1200 L          | Slate 60x120 3D Ash          |
| FL MARMI MARFIL SM 600X1200 IV L       | Marfil 60x120 Marble Ivory   |
| FL MARMI MIDLANDS SS 600X1200 GR L     | Midlands 60x120 Marble Grey  |
| FL SKYLINE PARIS VL RKLT 600X1200GR L  | Paris 60x120 Concrete Grey   |
| FL MARMI NAXOS SS 600X1200 GR L        | Naxos 60x120 Marble Grey     |
| FL MARMI VOLAKAS SS 600X1200 WT L      | Volakas 60x120 Marble White  |
| FL SKYLINE ONTARIO SM 600X1200 GR L CP | Ontario 60x120 Concrete Grey |
