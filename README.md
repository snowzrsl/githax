# GitHax - Authentication and Monitoring System

## 📋 Description
GitHax is an advanced authentication and monitoring system developed in Python, featuring a modern graphical interface and integrated security features.

## 🚀 Main Features
- Modern and intuitive graphical interface
- Machine-specific unique authentication code system
- Real-time monitoring of suspicious processes and files
- Multi-language support (English, Portuguese, and Spanish)
- Integrated anti-cheat system
- Encrypted data persistence
- System tray minimization

## 🔧 System Requirements
- Windows 10 or higher
- Python 3.8+
- Required libraries (see requirements.txt)

## 📦 Dependencies
```
customtkinter
psutil
pywin32
cryptography
requests
pillow
watchdog
pystray
rarfile
py7zr
```

## 🛠️ Installation
1. Clone the repository or download the files
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the program:
```bash
python main.py
```

## 🔐 Security Features
- Detection and blocking of known cheats and hacks
- Suspicious file monitoring
- Protection against unauthorized closure
- Real-time Discord alerts
- Sensitive data encryption
- Windows registry credential backup

## 🌐 Language Support
- 🇺🇸 English (US)
- 🇧🇷 Portuguese (BR)
- 🇪🇸 Spanish

## ⚙️ Configuration
The system uses Discord webhooks for notifications. Configure the webhooks in the `main.py` file:
- WEBHOOK_CONFIRM: For authentication confirmations
- WEBHOOK_ALERT: For security alerts

## 🔍 Monitoring
The system constantly monitors:
- Suspicious processes
- Files with specific extensions
- Cheat attempts
- Suspicious browser extensions
- Compressed files with suspicious content

## 🚫 Anti-Cheat
Detects and blocks:
- Cheat Engine and variants
- AutoHotkey scripts
- Known trainers and hacks
- DLL injectors
- Macros and bots

## 📝 Logs and Alerts
- Real-time Discord alerts
- Violation attempt logging
- Suspicious file monitoring
- Authentication notifications

## ⚠️ Notes
- The program cannot be closed normally (security measure)
- Minimizes to system tray when closure is attempted
- Requires administrator permissions for some features
- Maintains credential backup in Windows registry

## 🤝 Contributing
Contributions are welcome! Please read the contribution guidelines before submitting pull requests.

## 📄 License
This project is under the MIT License. See the LICENSE file for more details. 
