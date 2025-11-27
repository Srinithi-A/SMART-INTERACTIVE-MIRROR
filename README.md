
🪞 Smart Interactive Mirror

A lightweight IoT smart mirror built using the Arduino UNO R4 WiFi board, Web server- serving a fully responsive web interface that displays live time, weather info, and streams the phone/PC camera through the browser — all over the same local Wi-Fi network.
This project combines embedded programming with web technologies to create an interactive, affordable, and easy-to-use smart mirror experience.
🚀 Features
Built-in Web Server: Arduino UNO R4 WiFi hosts a local web page accessible from any device on the same network.
Real-Time Display: Shows live date and time using JavaScript.
Camera Integration: Streams the device’s camera feed inside the mirror UI using getUserMedia() (no extra hardware required).
LED Matrix Display: Uses the onboard LED matrix to show scrolling welcome messages and alerts.
Smooth Wi-Fi Connectivity: Automatically connects to local Wi-Fi and displays IP address for easy access.
Responsive UI: Styled using pure HTML and CSS for a clean neon-mirror effect.

🧠 Tech Stack
Arduino UNO R4 WiFi
WiFiS3 Library – Wi-Fi connectivity
ArduinoGraphics & Arduino_LED_Matrix – Text rendering and LED animations
HTML, CSS, JavaScript – Web interface
Local Camera Streaming – Browser mediaDevices.getUserMedia() API

📸 How It Works
The Arduino connects to Wi-Fi and starts a local server on port 80.
When accessed through the browser, it serves an HTML page with:
Live clock
Weather placeholder
Camera feed
User’s device camera becomes the mirror view.
LED matrix scrolls messages such as “SMART MIRROR” and “HAPPY DAY!!!!” every 20 seconds.
Upload the sketch to your Arduino UNO R4 WiFi.
Open Serial Monitor → note the printed IP address.

Enter the IP address in your phone or laptop browser.

The Smart Mirror interface loads automatically with camera feed.
