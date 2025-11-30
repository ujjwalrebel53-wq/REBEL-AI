# Rebel Ai Project

## Project Overview
This is a vanilla HTML/CSS/JS landing page for "Rebel Ai", created by Rebel bhaiya. It features a modern dark theme, smooth animations, and a responsive layout.

**Tagline**: "Unleash the Code."
**Description**: An advanced AI assistant designed for those who dare to think differently. Powered by cutting-edge technology and a rebellious spirit.

## Architecture
- **Entry Point**: `index.html`
- **Styles**: `css/style.css` - Contains all global styles, variables, and animations. Uses CSS variables for easy theming.
- **Scripts**: `js/main.js` - Handles scroll animations, smooth scrolling, modal interactions, and the Rebel Gpt chatbot integration.
- **Configuration**: `yw_manifest.json` - Stores AI configuration (model, prompts) for the Youware AI SDK.

## Development
- **Build**: No build step required. Open `index.html` in a browser.
- **Dependencies**:
  - Font Awesome (CDN)
  - Google Fonts (Roboto)
  - Youware AI SDK (CDN) - `youware-ai`, `youware-openai`

## Key Features
- **Smooth Scrolling**: Enabled globally via CSS `scroll-behavior: smooth` and enhanced with JS for offset handling.
- **Reveal Animations**: Elements with class `.animate` fade in when scrolling into view.
- **Responsive Design**: Mobile-friendly layout with media queries.
- **Rebel Gpt Chatbot**: Integrated chatbot using Youware AI SDK (DeepSeek V3 model) for real-time AI interactions.
  - **Configuration**: Managed via `yw_manifest.json`.
  - **Integration**: `js/main.js` uses `window.aiSdk` to communicate with the AI API.
  - **Mobile Optimization**: Full-screen chat interface with safe-area support (`viewport-fit=cover`) and touch-optimized controls.
- **About Developer Modal**: Information about Rebel Bhaiya.

## Commands
- **Lint**: No linter configured.
- **Test**: No tests configured.
- **Run**: Open `index.html` in a browser.
