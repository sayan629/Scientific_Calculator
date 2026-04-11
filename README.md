# 🧮 Sayan's Scientific Calculator

A sleek, dark-themed **Scientific Calculator** built with pure HTML, CSS, and JavaScript — no frameworks, no dependencies. Features a glowing teal terminal aesthetic with full scientific functionality.

---

## ✨ Features

### 🔢 Basic Operations
- Addition, Subtraction, Multiplication, Division
- Decimal input, Positive/Negative toggle (`±`)
- Percentage (`%`)
- Clear All (`C`) and Clear Entry (`CE`)
- Backspace support

### 🔬 Scientific Functions
| Button | Function |
|--------|----------|
| `sin` `cos` `tan` | Trigonometric functions |
| `sin⁻¹` `cos⁻¹` `tan⁻¹` | Inverse trigonometric functions |
| `log` | Base-10 logarithm |
| `ln` | Natural logarithm |
| `log₂` | Base-2 logarithm |
| `eˣ` | Exponential (e raised to x) |
| `x²` | Square |
| `x³` | Cube |
| `√x` | Square root |
| `∛x` | Cube root |
| `xʸ` | Power (x to the y) |
| `ˣ√y` | nth root of y |
| `n!` | Factorial |
| `\|x\|` | Absolute value |

### 📐 Constants
- `π` — Pi (3.14159...)
- `e` — Euler's number (2.71828...)

### 🧠 Memory Functions
| Button | Action |
|--------|--------|
| `MC` | Memory Clear |
| `MR` | Memory Recall |
| `MS` | Memory Store |
| `M+` | Add to Memory |
| `M−` | Subtract from Memory |

### 🌀 Angle Modes
- **DEG** — Degrees (default)
- **RAD** — Radians
- Toggle via the top-right pills on the calculator

---

## 🖥️ Display
- **Owner tag** — `✦ S A Y A N ✦` with animated shimmer gradient
- **Expression line** — shows the current operation (e.g. `sin(45) =`)
- **History line** — shows the last completed calculation
- **Main display** — large Orbitron font with teal glow; auto-shrinks for long numbers
- **Error state** — turns red on invalid operations (e.g. `√(-1)`, `1/0`)

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0–9` | Digit input |
| `.` | Decimal point |
| `+` `-` `*` `/` | Operators |
| `^` | Power (xʸ) |
| `Enter` or `=` | Equals |
| `Escape` | Clear All |
| `Delete` | Clear Entry |
| `Backspace` | Delete last digit |

---

## 🚀 Getting Started

No installation required. Just open the file in any modern browser.

```bash
# Clone or download the file
open index.html
```

Or simply double-click `index.html` to launch it in your default browser.

---

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure |
| CSS3 | Styling, animations, gradients |
| Vanilla JavaScript | All calculator logic |
| [Orbitron](https://fonts.google.com/specimen/Orbitron) | Display font |
| [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) | Button / UI font |

---

## 📁 File Structure

```
index.html        ← Single self-contained file (HTML + CSS + JS)
README.md         ← This file
```

---

## 🎨 Design Highlights

- **Dark terminal aesthetic** with deep navy/black backgrounds
- **Teal glow** (`#00c896`) accent color throughout
- **3D press-depth buttons** with colored shadow layers
- **Ripple animation** on every button click
- **Shimmer gradient** on the owner name in the display
- **Color-coded buttons** — numbers (blue), operators (teal), functions (cyan), memory (gold), clear (red), equals (bright teal)

---

## 👤 Author

**Sayan**
> Built with passion for clean UI and powerful functionality.

---

## 📄 License

This project is open source and free to use for personal and educational purposes.
