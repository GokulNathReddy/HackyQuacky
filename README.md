# HackyQuacky 🦆  
> A USB Rubber Ducky Payload to extract browser passwords, Wi-Fi credentials, Windows product keys, and system information—all saved to the device itself.

## 🚀 Features
- **Browser Passwords**: Extracts saved passwords from popular browsers.  
- **Wi-Fi Passwords**: Retrieves saved Wi-Fi credentials.  
- **Windows Product Key**: Captures the Windows product key.  
- **Hardware & Software Info**: Collects detailed system specifications.  
- **Offline Storage**: Saves all the collected data directly to the USB device.

---

## 📁 Project Structure
```plaintext
HackyQuacky/
│
├── payload.dd         # Rubber Ducky payload script
├── sy_cred.ps1         # PowerShell script for data extraction
└── README.md           # Project documentation

🛡️ **Disclaimer**  
This project is for **educational purposes only**. Unauthorized access to devices or data is **illegal** and punishable by law. Use this tool responsibly and only with proper authorization.

---

✨ **How to Use**  

**Set Up the USB Rubber Ducky:**  
- Load the `payload.dd` onto your Rubber Ducky device.  
- Ensure the `sy_cred.ps1` script is accessible by the payload.  

**Deploy:**  
- Insert the USB into the target device.  
- The script will run automatically, collecting and storing data on the USB.  

**Retrieve Data:**  
- Open the USB device to view the collected data files.

---

💡 **Customization**  
Feel free to modify the `payload.dd` or `sy_cred.ps1` script to add/remove features or change storage behavior.

---

📢 **Contribute**  
Found a bug or have an idea for improvement? Open an issue or submit a pull request! Contributions are welcome.

---

⚠️ **Warning**  
Using **HackyQuacky** maliciously or without permission can have serious consequences. Always ensure you are operating within legal boundaries.

---

Enjoy responsibly! 🦆

