# ⚡ The Real-Time Velocity Typing Engine

<p align="center">
  <img src="CSC LOGO.png" alt="CSC Logo" height="80"/>
  &nbsp;&nbsp;&nbsp;
  <img src="cyberspace black.png" alt="CyberSpace Logo" height="80"/>
  &nbsp;&nbsp;&nbsp;
  <img src="Novus_Full_White (1).png" alt="Novus Logo" height="80"/>
</p>

<p align="center">
  <strong>A professional-grade, real-time typing test engine</strong><br/>
  Built with Vanilla HTML, CSS, and JavaScript
</p>

---

## 🚀 Overview

**The Real-Time Velocity Typing Engine** is a high-performance typing benchmark system designed to evaluate **speed, accuracy, and consistency** under real-time constraints.

The engine strictly avoids standard input fields and instead operates at the **character-rendering level**, making it suitable for competitive environments and technical evaluations.

---

## ✨ Key Features

- ⌨️ **No Input Fields**
  - No `<input>` or `<textarea>` used
  - Global keyboard event handling
  - Character-by-character `<span>` rendering

- 🔤 **Character-Level Accuracy Engine**
  - Active character index tracking
  - Correct characters shown in white
  - Incorrect characters shown in red with underline
  - Full backspace rollback support

- 📊 **Live Performance Metrics**
  - **Words Per Minute (WPM)**  
    `(Correct Characters ÷ 5) ÷ Minutes Elapsed`
  - **Accuracy (%)**  
    `(Correct Keystrokes ÷ Total Keystrokes) × 100`

- ⏱ **One-Minute Typing Challenge**
  - Timer starts on first keystroke
  - Hard stop at 60 seconds
  - Results popup with final score summary

- ♾ **Unlimited, Non-Repeating Text**
  - Procedural word-stream generator
  - No sentence memorization
  - Offline-safe and performance optimized

- ⚡ **Velocity Glow Feedback**
  - UI glow activates when WPM exceeds **80**
  - Real-time visual performance feedback

- 🎨 **Tech-Inspired UI**
  - Animated grid background
  - Floating cyber HUD elements
  - Neon glow styling
  - Clean, distraction-free layout

---

## 🧠 Why This Engine Stands Out

Unlike basic typing applications, this engine:

- Tracks typing at the **engine level**, not via browser-managed inputs
- Maintains accuracy at **100+ WPM**
- Prevents memorization advantages
- Mimics the feel of professional typing platforms (Monkeytype-inspired)
- Is built as a **system**, not a demo

---

## 🛠 Tech Stack

- **HTML5** — Semantic structure
- **CSS3** — Animations, layout, visual effects
- **JavaScript (Vanilla)** — Core typing engine and metrics logic

> No frameworks. No libraries. No dependencies.

---

## 📂 Project Structure

```text
/
├── index.html
├── README.md
├── CSC LOGO.png
├── cyberspace black.png
└── Novus_Full_White (1).png
