# 🥁 Drum Kit

> An interactive drum kit website built with **HTML, CSS, and JavaScript**, featuring click and keyboard controls, drum sounds, and button animations.

<div align="center">

### 🌐 Live Demo

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-View_Project-2ea44f?style=for-the-badge)](https://godsonvo-git.github.io/drum-kit-web/)

</div>

---

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

---

## 📸 Preview

![Drum Kit Preview] <img width="1917" height="900" alt="Screenshot 2026-09-23 170219" src="https://github.com/user-attachments/assets/02f2493a-0a3d-4ce0-9866-88fde7816a80" />


---

## ✨ Overview

**Drum Kit** is an interactive web project created using **HTML, CSS, and JavaScript**.

The application allows users to play different drum sounds by either **clicking the drum buttons** or pressing the corresponding **keyboard keys**.

Each drum button is connected to a different sound, while JavaScript handles audio playback and button animations.

---

## 🚀 Features

- 🥁 Seven different drum sounds
- 🖱️ Click-based drum controls
- ⌨️ Keyboard controls
- 🔊 Audio playback using JavaScript
- ✨ Button press animations
- 🎨 Drum-themed button backgrounds
- 💫 Visual feedback when a drum is played
- ⚡ Lightweight and fast
- 🧩 Built with Vanilla JavaScript

---

## ⌨️ Keyboard Controls

| Key | Sound |
|---|---|
| `W` | 🥁 Tom 1 |
| `A` | 🥁 Tom 2 |
| `S` | 🥁 Tom 3 |
| `D` | 🥁 Tom 4 |
| `J` | 🥁 Snare |
| `K` | 💥 Crash |
| `L` | 🥁 Kick Bass |

You can also play each sound by clicking the corresponding drum button.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **HTML5** | Structure of the drum kit |
| **CSS3** | Styling, layout, backgrounds, and animations |
| **JavaScript** | Audio playback, event handling, and button animation |
| **Google Fonts** | Arvo font for the interface |

---

## 🧠 JavaScript Concepts Practiced

This project helped me practice several JavaScript fundamentals:

- DOM element selection
- `querySelector()`
- `querySelectorAll()`
- `addEventListener()`
- Click events
- Keyboard events
- Functions
- `switch` statements
- `this`
- `event.key`
- `Audio()` objects
- `.play()`
- `classList.add()`
- `classList.remove()`
- `setTimeout()`
- Dynamic class selection

---

## 🔄 How It Works

```text
🖱️ Click Button        ⌨️ Press Keyboard Key
       ↓                         ↓
       └──────────┬──────────────┘
                  ↓
           Detect Key / Button
                  ↓
             makeSound()
                  ↓
          Create Audio Object
                  ↓
             Play Sound 🔊
                  ↓
         buttonAnimation()
                  ↓
          Visual Feedback ✨
