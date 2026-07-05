# 🧮 Fizz's Calculator

A big-button, colorful calculator made for kids — no install, no accounts, just open and tap.

Open **`kid_calculator.html`** in any web browser (Chrome, Safari, Edge, Firefox) on a computer, tablet, or phone. That's it — there's nothing to install.

---

## What's inside

Fizz's Calculator has two modes, switched with the tabs at the top.

### 🧮 Calculator
A simple, standard calculator for the four basic operations:

| Button | What it does |
|---|---|
| `0`–`9` | Enter numbers |
| `+` `−` `×` `÷` | Add, subtract, multiply, divide |
| `.` | Decimal point |
| `±` | Switch a number between positive and negative |
| `⌫` | Erase the last digit |
| `C` | Clear everything and start over |
| `=` | Show the answer |

Operations can be chained just like a real calculator: `3 + 5 + 2 =` gives `10`.

Dividing by zero doesn't throw a scary error — Fizz just says **"Oops! Can't ÷ 0"** and gives a little shake.

Fizz's face reacts to what happens:

| Face | When it shows up |
|---|---|
| 😊 | Just sitting there, ready to help |
| 🤔 | Thinking, right after you pick an operation |
| 😄 | A normal, happy answer |
| 🤩 | A big number (1,000 or more)! |
| 😎 | A cool answer (like a negative number) |
| 😵 | Oops — tried to divide by zero |

### 🧩 Number Grids
A friendly, kid-sized introduction to matrices — no jargon, just boxes and buttons.

1. **Pick a size** — 2×2, 2×3, or 3×3
2. **Fill in Grid A** (and Grid B, if needed) by tapping each box and typing a number
3. **Pick what to do:**
   - ➕ **Put Together** — adds Grid A and Grid B, box by box
   - ➖ **Take Away** — subtracts Grid B from Grid A, box by box
   - ✨ **Make Bigger** — multiplies every box in Grid A by a number you choose
   - 🔄 **Spin It** — flips Grid A so rows become columns (a transpose)
4. Tap **"Show Me! ✨"** — the answer appears as its own grid, with a short message explaining what just happened

Matrix multiplication, determinants, and inverses are intentionally left out — those ideas are better suited for older kids/teens. (Ask if you'd like a "big kid" version that adds them.)

---

## Who it's for

Designed for roughly ages 5–10: large tap targets, no small text, no typing symbols like commas or brackets, and friendly wording instead of math terminology ("Put Together" instead of "matrix addition").

A grown-up helping out can also use a keyboard on the Calculator tab (number keys, `+ - * /`, `Enter` for `=`, `Backspace`, `Escape` to clear).

## Requirements

- Any modern web browser
- An internet connection on first load (to fetch the "Baloo 2" font from Google Fonts) — the calculator still works without it, just with a fallback font

## Files

| File | Description |
|---|---|
| `kid_calculator.html` | The whole app — HTML, styling, and logic in one file |

No build steps, no dependencies, no server required.
