# AgriGuard
AgriGuard — Smart Farming Dashboard UI
A responsive front-end prototype for the AgriGuard IoT project, built with plain HTML, CSS, and JavaScript.
Features
- Farm overview cards for soil moisture, intrusion alerts, pump status, and sensor status
- Interactive soil-moisture slider and circular gauge
- Demo irrigation pump ON/OFF controls
- Sample sensor health panel for PIR, ultrasonic, and soil-moisture sensors
- Activity timeline with clear action
- Sample weekly moisture chart and field-care note
- Field-zone cards with progress indicators
- Buttons to simulate an intrusion alert and run a UI demo check
- Light/dark theme toggle; theme preference is saved in the browser when local storage is available
- Responsive layout for desktop, tablet, and mobile screens
- Gradient-rich sage, magenta, blush, and lavender color palette
Run locally
1. Put index.html in your project folder.
2. Open the folder in Visual Studio Code.
3. Open index.html and use Live Server (if installed), or open the HTML file directly in a browser.
4. No React, npm, build step, or backend is required for this UI prototype.
Will it run everywhere?
The page can run in modern browsers on Windows, macOS, Linux, Android, and iOS. It can run locally on your computer without an internet connection, although the optional Google Fonts import may fall back to system fonts when offline.

To make the website available to other people over the internet, you must deploy it to a hosting service (for example, GitHub Pages, Netlify, or Vercel) or host it on your own server. A local Live Server address such as 127.0.0.1 or localhost is only accessible from your computer by default; it is not automatically a public website.
Important project limitation
This is currently a simulated front-end prototype. The displayed sensor readings, weekly chart, zone cards, alerts, and pump controls are demo content. The buttons do not communicate with the ESP32, Firebase, or a physical water pump yet. Hardware/data integration will require the team's chosen backend or communication method.
Suggested project structure
AgriGuard/
├── index.html
└── README.md
