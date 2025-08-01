# Invisible-Anti-Phishing-Browser-Extension

![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/github/v/tag/abdyar/Invisible-Anti-Phishing-Browser-Extension)

Invisible Anti-Phishing Shield silently blocks phishing and malicious websites in real time. It runs entirely in the background with no interface, no popups, and no data collection—providing lightweight, privacy-friendly protection while you browse.

A lightweight, fully invisible Chrome browser extension that silently blocks phishing and malicious websites using Chrome Manifest V3 and the Declarative Net Request API. It runs entirely in the background with no UI or data collection.

## Features

- Blocks known phishing URLs instantly and silently  
- Runs with zero user interface (no icons, popups, or settings)  
- Privacy-first: no user data collected or sent anywhere  
- Built with Manifest V3 for compatibility with the latest Chrome versions

## Installation

1. Clone or download this repository  
   ```bash
   git clone https://github.com/abdyar/Invisible-Anti-Phishing-Browser-Extension.git
2. Open Chrome and navigate to chrome://extensions/

3. Enable Developer mode (top right)

4. Click Load unpacked and select the project folder

5. The extension will start running silently in the background

## Usage
No UI or interaction needed

The extension automatically blocks phishing domains listed in rules.json

To add or update blocked sites, edit the rules.json file and reload the extension

## Development
Manifest V3 extension with background service worker (background.js)

Blocking rules defined in rules.json using Chrome Declarative Net Request API

## Contributing
Contributions are welcome! Please open issues or submit pull requests for improvements and new features.

## License
MIT
