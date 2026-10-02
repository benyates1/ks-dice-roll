# 🎲 Daily Dice Task Roller

A sleek, minimalist web application designed to give users a single, focused objective each day. Built with a striking dark UI featuring off-blacks, deep grays, and dark crimson accents.

## ✨ Features

- **Interactive 3D-Style Dice:** A smooth rolling animation that randomly selects your fate.
- **24-Hour Cooldown restriction:** Utilizes browser `localStorage` to enforce a strict one-roll-per-day rule. 
- **Live Countdown Timer:** Shows returning users exactly when they are eligible to roll again.
- **Dynamic Data:** Tasks are easily configurable via a simple JSON-style object in the code.
- **Immersive UI:** Default browser behaviors like text highlighting, element dragging, and right-click context menus are disabled for a native app feel.
- **Developer Bypass:** Built-in toggle to disable the 24-hour lockout for rapid testing.

## 🚀 Getting Started

This project is built using Vanilla JavaScript, HTML5, and Tailwind CSS (via CDN). There is no build step or backend required.

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```
2. Open `index.html` in any modern web browser.

## 🛠️ Configuration & Testing

### Changing the Tasks
You can easily modify the tasks assigned to each dice roll by editing the `rollOutcomes` object inside the `<script>` tag in `index.html`:

```javascript
const rollOutcomes = {
    "1": "Your custom task for rolling a 1",
    "2": "Your custom task for rolling a 2",
    // ...
};
```

### Developer Bypass Mode
If you want to test the app without having to wait 24 hours between rolls, you can enable the bypass toggle. At the top of the `<script>` tag, change the `BYPASS_COOLDOWN` constant to `true`:

```javascript
// Set to true to bypass the 24-hour wait period for testing
const BYPASS_COOLDOWN = true; 
```

## 📄 License & Usage

I have released the source code for this project for **personal use**. Feel free to explore the implementation, download it, and tweak it for your own personal daily routines and private projects!