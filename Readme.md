# 🧮 Calculator

A sleek, dark-themed calculator built with vanilla HTML, CSS, and JavaScript. Supports all four arithmetic operations, keyboard input, chained calculations, and a live calculation history — zero dependencies.

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/license-MIT-green?style=flat)

---

## ✨ Features

- **Arithmetic operations** — Addition, Subtraction, Multiplication, Division
- **Chained calculations** — Chain multiple operations without pressing equals
- **Keyboard support** — Full keyboard bindings for fast input
- **Live expression preview** — Shows the current expression above the result
- **Calculation history** — Last 5 calculations stored; click any to recall
- **Percentage & sign toggle** — `%` and `±` buttons built in
- **Divide-by-zero handling** — Graceful error with auto-reset
- **Dynamic font scaling** — Long numbers shrink to fit the display
- **Backspace support** — Delete the last digit with `Backspace`

---

## 🚀 Demo

Just open `calculator.html` in any modern browser — no build step, no dependencies.

```bash
# Clone the repo
git clone https://github.com/your-username/calculator.git

# Open in browser
open calculator.html
```

---

## 🎹 Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `0` – `9` | Input digits |
| `+` `-` `*` `/` | Operators |
| `Enter` or `=` | Equals |
| `.` | Decimal point |
| `%` | Percentage |
| `F9` | Toggle sign (±) |
| `Backspace` | Delete last digit |
| `Escape` | Clear (C / AC) |

---

## 📁 Project Structure

```
calculator/
└── calculator.html    # All-in-one file (HTML + CSS + JS)
```

---

## 🛠️ Built With

- **HTML5** — Structure and layout
- **CSS3** — Dark theme, animations, transitions, grid layout
- **Vanilla JavaScript** — All logic, state management, keyboard events
- **Google Fonts** — DM Mono (display) + Space Grotesk (UI)

---

## 🧠 How It Works

The calculator maintains four pieces of state:

| Variable | Purpose |
|----------|---------|
| `currentVal` | The number currently being entered |
| `prevVal` | The first operand, stored after an operator is pressed |
| `operator` | The pending operation (`+`, `−`, `×`, `÷`) |
| `waitingForOperand` | Whether the next digit starts a new number |

When an operator is pressed while one is already pending, the intermediate result is computed first (enabling chaining). The `=` key performs the final calculation and logs it to history.

---

## 📸 Preview

> Dark-themed UI with a monospace display, soft purple operator buttons, and a glowing equals key.

---

## 📄 License

This project is open source under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

Built as part of a frontend development practice task. Inspired by the clean aesthetics of modern mobile calculators.
