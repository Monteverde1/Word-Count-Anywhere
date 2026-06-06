A lightweight Chrome extension that instantly shows word count, character count, sentence count, and reading time for any selected text on any webpage. No popups, no signup, no tracking.

## How It Works

1. Select any text on any webpage
2. Right-click
3. Click **Word Count**
4. A toast notification appears with your stats

## Stats Shown

- Word count
- Character count (with and without spaces)
- Sentence count
- Estimated reading time

## Tech

- Manifest V3
- Vanilla JavaScript
- Chrome APIs: `contextMenus`, `scripting`, `activeTab`
- Zero dependencies
- No backend
- No data collection

## Install

Available on the [Chrome Web Store](#).

Or load unpacked locally:

1. Clone this repo
2. Open `chrome://extensions`
3. Enable Developer Mode
4. Click **Load unpacked** and select the folder

## Privacy

This extension collects no user data, transmits nothing, and stores nothing. All logic runs locally in the browser.
