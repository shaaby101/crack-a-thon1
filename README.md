# The Ultimate AI Presenter

## Overview
A powerful single-file HTML web application that creates AI-generated presentations with gesture control. Using the Google Gemini API, it generates dynamic presentations on any topic that you can control with hand gestures via your webcam.

## Key Features

### 🤖 AI-Powered Content
- Automatic slide generation using Gemini API
- Topic-based content creation
- Smart theme-aware content styling

### 🎨 Visual Themes
1. **Retro-Futuristic**
   - Cyberpunk terminal-style aesthetic
2. **Educational**
   - Clean, minimalist design for professional use
3. **Creative**
   - Playful and colorful interface

### ✋ Gesture Controls
- **Right Hand Up**: Next slide
- **Left Hand Up**: Previous slide
- Hands-free navigation using TensorFlow.js

## Technology Stack

### Core Technologies
- 🌐 HTML5 & CSS3
- 💅 Tailwind CSS (CDN)
- 📜 Vanilla JavaScript (ES Modules)

### AI & Processing
- 🧠 Google Gemini API
- 📸 TensorFlow.js (MoveNet)
- ⚡ Marked.js

## Setup Instructions

### 1. Get API Key
1. Visit Google AI Studio
2. Create a new API key

### 2. Configure Application
```javascript
// Find this line in ai.html
const apiKey = "YOUR_API_KEY_HERE";
```

### 3. Launch
1. Open `ai.html` in a modern browser
2. Grant webcam permissions
3. Start presenting!

## How It Works

1. **Input**: Select theme and enter topic
2. **Processing**: Gemini API generates slide content
3. **Display**: Content rendered with theme styling
4. **Control**: Real-time gesture detection via webcam
5. **Navigation**: Hand movements trigger slide changes

---
*Built with ❤️ using Google Gemini API and TensorFlow.js*
