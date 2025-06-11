# ESP8266 Room Light Controller 

A lightweight Wi-Fi-based smart room light controller built with the **ESP8266 NodeMCU**. This project allows you to **turn ON/OFF your room light**, **schedule actions**, and enjoy a responsive **dark mode UI** — all without internet access.


##  Features

- **Access Point Mode** – Works offline, no router needed
- **Web-Based Control UI** – Built with HTML & CSS
- **Scheduler** – Set ON/OFF time for automation
- **Dark Mode** – Toggle between light and dark themes
-  **Relay Control** – Active LOW logic for switching
- Simple and secure (AP password protected)

---

## 🛠 Hardware Requirements

- ESP8266 NodeMCU
- 1-Channel Relay Module (active LOW)
- LED/Bulb with relay-safe power supply
- Jumper Wires & Power Source

---

##  How It Works

1. ESP8266 creates a Wi-Fi hotspot named `BHB-Relay`
2. User connects to the AP and accesses the control panel at `192.168.4.1`
3. Relay is toggled via `/on` and `/off` routes
4. Scheduler runs in the frontend using JavaScript
5. Optional: Add WebSocket support in the future for real-time updates

---

## 📷 UI Snapshot

> Add a screenshot or video GIF here

---

## Getting Started

1. Flash the code using Arduino IDE or PlatformIO
2. Open Serial Monitor to check if AP is created
3. Connect to `BHB-Relay` with password `12345678`
4. Go to `192.168.4.1` in a browser
5. Enjoy controlling your light wirelessly

---

## Developed By

**Mr. BHB**  
Student | Developer | IoT Enthusiast  
 • [Facebook](https://www.facebook.com/mr.basirulhb)


## License

This project is licensed under the MIT License.



** Star this repo if you like it!**

