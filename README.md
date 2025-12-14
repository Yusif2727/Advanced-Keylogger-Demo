# Advanced-Keylogger-Demo
Keylogger for educational purposes
# 💻 System Reporter (Python)

This project is a simple, multi-threaded Python script designed to monitor system activity. It captures keyboard input (keylogging) and takes periodic screenshots, sending the collected data to an external endpoint (e.g., Discord Webhook) at set intervals.

## ⚠️ Disclaimer and Ethical Use

This tool is created strictly for **educational and personal assessment purposes** (e.g., self-monitoring or internal testing). Misuse of this script against individuals or systems without explicit permission is illegal and unethical. The developer is not responsible for any misuse.

## 🛠 Required Libraries (Dependencies)

This script requires the following external Python packages to function correctly:

| Library | Purpose |
| :--- | :--- |
| `requests` | Handles all HTTP requests for sending data (logs and screenshots) to the Discord Webhook. |
| `pynput` | Used to listen to and log keyboard events (keystrokes). |
| `pyscreenshot` | Used to capture the current screen image. |
| `Pillow` (PIL) | An essential image processing library required by `pyscreenshot` to save and handle image data. |

### ⚙️ Installation Command

You can install all required dependencies using a single command in your terminal:

```bash
pip install requests pynput pyscreenshot Pillow
