# Canvas Tab Shield

A professional Chrome extension that provides protection against Canvas tab switching detection and AI Trojan Horse tracking elements.

## Features

### 🔒 Tab Switching Protection
- Prevents Canvas from detecting when you switch between tabs
- Overrides visibility state properties
- Blocks detection event listeners
- Maintains focus state

### 🛡️ AI Trojan Horse Protection
- Removes hidden tracking elements from Canvas assignments
- Monitors for dynamic content changes
- Automatically detects Canvas environment
- Protects against hidden surveillance elements

### ⚙️ User-Friendly Controls
- Simple on/off toggle
- Real-time status indicators
- Clean, modern interface
- Persistent settings

## Installation

1. Download the extension files
2. Open Chrome and go to `chrome://extensions/`
3. Enable "Developer mode" in the top right
4. Click "Load unpacked" and select the extension folder
5. The extension icon will appear in your toolbar

## Usage

1. **Enable Protection**: Click the extension icon and toggle the protection switch to "ON"
2. **Visit Canvas**: Navigate to any Canvas learning management system
3. **Automatic Protection**: The extension will automatically detect Canvas and apply protection
4. **Status Monitoring**: Check the extension popup to see protection status

## How It Works

### Tab Switching Protection
The extension overrides key browser APIs that Canvas uses to detect tab switching:
- `document.visibilityState`
- `document.hidden`
- `Document.prototype.hasFocus`
- Event listeners for `focus`, `blur`, `visibilitychange`, etc.

### AI Trojan Horse Protection
Automatically detects and removes hidden tracking elements:
- Monitors for `span[aria-hidden="true"]` elements
- Targets specific Canvas content wrappers
- Uses MutationObserver for dynamic content
- Safely removes or hides tracking elements

## Privacy & Security

- **No Data Collection**: The extension does not collect, store, or transmit any user data
- **Local Storage Only**: Settings are stored locally in your browser
- **No External Requests**: The extension operates entirely offline
- **Open Source**: All code is transparent and auditable

## Compatibility

- **Browser**: Google Chrome (Manifest V3)
- **Canvas Versions**: Compatible with all Canvas LMS versions
- **Operating Systems**: Windows, macOS, Linux

## Support

If you encounter any issues:
1. Check that the extension is enabled
2. Refresh the Canvas page
3. Try disabling and re-enabling the extension
4. Ensure you're using a supported browser version

## Version History

### v0.0.0.1
- Initial Chrome Web Store release
- Enhanced protection algorithms
- Improved user interface design
- Better error handling and logging
- Modern CSS styling with dark theme support

### v0.0.0.0
- Initial development release
- Basic tab switching protection
- AI Trojan Horse protection
- Core functionality implementation

## Legal Notice

This extension is provided for educational and legitimate academic use. Users are responsible for complying with their institution's academic integrity policies. The developers are not responsible for any misuse of this software.

## License

This project is open source and available under the MIT License.

---

**Note**: This extension is designed to protect legitimate academic work and should be used in accordance with your institution's policies.
