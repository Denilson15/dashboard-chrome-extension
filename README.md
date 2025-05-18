# 🧭 Dashboard Chrome Extension

A minimalist Chrome extension that transforms your new tab into a personalized dashboard featuring a real-time clock, dynamic greeting, and an inspirational quote. Built with **HTML**, **CSS**, and **JavaScript**, and bundled using **Vite** for efficient development and deployment.

> 💡 No AI was used in the development of this project. AI tools were utilized solely for documentation purposes, such as generating this README. I believe in building a strong foundation in programming while also learning how to effectively use AI tools as part of a modern developer workflow.

## ✨ Features

- 🕒 **Live Clock**: Displays the current time, updating every second.
- 👋 **Dynamic Greeting**: Personalized greeting based on the time of day (e.g., "Good Morning").
- 💬 **Inspirational Quote**: Fetches and displays a random quote to motivate users.
- 🎨 **Clean UI**: Simple and responsive design for an uncluttered new tab experience.

## 📦 Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Vite (Build Tool)

## 🚀 Getting Started

### Installation

```bash
git clone https://github.com/Denilson15/dashboard-chrome-extension.git
cd dashboard-chrome-extension
npm install
npm run build
```

### Load the Extension in Chrome

1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable **Developer mode** (toggle in the top right).
3. Click **Load unpacked** and select the `dist` folder in your project directory.

Enjoy your new tab dashboard!

## 📁 File Structure

```
dashboard-chrome-extension/
├── dist/               # Compiled extension ready for deployment
├── index.html          # Main HTML file
├── index.css           # Stylesheet
├── index.js            # JavaScript logic
├── manifest.json       # Chrome extension manifest
├── package.json        # Project metadata and scripts
├── vite.config.js      # Vite configuration
└── README.md           # Project documentation
```
