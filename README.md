# ⚡ FluX | Minimalist Focus Engine

[**Live Demo »**](https://fluxxweb.netlify.app)

FluX is a high-precision, aesthetic productivity timer built for deep work. Unlike standard browser timers that drift when tabs are backgrounded, FluX utilizes timestamp-based logic to ensure millisecond accuracy during intense focus sessions.

![FluX Preview](preview.png)

---

## 🚀 Key Features

*   **Drift-Free Precision:** Uses `Date.now()` delta calculations to bypass browser background throttling.
*   **Three Deep Work Tiers:** 
    *   **Pomodoro:** 25m Focus / 5m Break.
    *   **Deep Work:** 90m Focus / 15m Break.
    *   **Monk Mode:** 180m Focus / 30m Break.
*   **Persistent Sessions:** Flow logs and timer states are saved to `localStorage`, so a page refresh never kills your progress.
*   **Glassmorphism UI:** A sleek, distraction-free interface designed for zero-clutter environments.
*   **Dynamic Progress Ring:** Real-time SVG visualization of your focus session.

## 🛠️ Tech Stack

*   **Frontend:** Vanilla JavaScript (ES6+), HTML5, CSS3.
*   **Storage:** Browser LocalStorage API.
*   **Audio:** High-fidelity notification pings for session transitions.

## 📦 Local Setup

1. Clone the repository:
   ```bash
   git clone [https://github.com/rudra-th/fluxxweb.git](https://github.com/rudra-th/fluxxweb.git)
