# Privacy Policy Summarizer Chrome Extension

**Gamified privacy protection – Level up while staying safe!**

## Overview

Privacy Policy Summarizer is a Chrome extension that analyzes the privacy practices of any website you visit. It summarizes what data is collected, how it's used, and potential privacy risks. The extension uses a gamified system to reward users for checking sites and avoiding risky ones.

## Features

- **Automatic Privacy Analysis:** Instantly summarizes privacy practices for any website.
- **Continuous Alerts:** Get privacy notifications every 30 seconds while browsing.
- **Gamification:** Earn XP, level up, and unlock achievements for protecting your privacy.
- **Badge Indicator:** Extension icon changes to reflect the privacy risk level of the current site.
- **AI Summarization (Optional):** Integrate with Gemini AI for advanced privacy policy summaries.

## How It Works

1. When you visit a website, the extension scans the page for privacy-related content.
2. It analyzes the text for patterns indicating data collection, usage, and risks.
3. A summary is generated and displayed in the popup, with color-coded highlights.
4. The extension badge updates to show the privacy risk level.
5. You earn points and achievements for checking sites and avoiding high-risk domains.

## Getting Started

### 1. Clone or Download the Repository

```sh
git clone https://github.com/yourusername/privacy-policy-summarizer.git
cd privacy-policy-summarizer
```

### 2. Add an Icon

Place a 128x128 PNG icon named `icon.png` in the `icons/` directory. You can use the included [create_icon.html](create_icon.html) to generate one.

### 3. Load the Extension in Chrome

1. Go to `chrome://extensions/`
2. Enable "Developer mode"
3. Click "Load unpacked"
4. Select the project directory

### 4. Usage

- Click the extension icon to view the privacy summary and your gamification stats.
- Use the "Check This Website" button to refresh the analysis.
- Toggle continuous alerts using the button in the popup.

## File Structure

- `manifest.json` – Chrome extension manifest
- `background.js` – Background service worker, privacy analysis, badge updates, gamification logic
- `content.js` – Injected into web pages, handles alerts and overlays
- `privacyGame.js` – Gamification system (XP, levels, achievements)
- `popup.html` / `popup.js` – Extension popup UI and logic
- `style.css` – Styling for the popup and notifications
- `aiSummarizer.js` – (Optional) Gemini AI-based summarization
- `icons/` – Extension icon and placeholder

## Privacy & Security

- All analysis is performed locally in your browser.
- No data is sent to external servers, except when using the optional Gemini AI summarizer.
- You can disable continuous alerts at any time.

## Credits

- Shield/lock icon generator based on [create_icon.html](create_icon.html)
- Gamification inspired by privacy education best practices

## License

MIT License

---

**Stay safe and level up your privacy!**