# ESP32-Rick-Roller
The one-stop shop solution for an ESP32-based Rick Rolling solution.

This README will be updated fully later. Until then, here are the dependencies used in this project.

# Dependencies - C++

WiFi.h
- This should be included with the Arduino IDE.

DNSServer.h
- In the flavor provided by Espressif.
- https://github.com/espressif/arduino-esp32

ESPAsyncWebServer.h
- Project looks not to be maintained, but it works fine.
- https://github.com/me-no-dev/ESPAsyncWebServer

AsyncTCP.h & SPIFFS.h
- These are part of ESPAsyncWebServer.

# Dependencies - Other

animate.css
- A fantastic lightweight library to replace most of what I used to use jQuery for
- The included file is modified to strip out the bulk I don't need
- Under MIT License
- https://github.com/daneden/animate.css

loading-bar
- A css/js library for creating loading bars with SVGs and other methods
- Under MIT License
- https://github.com/loadingio/loading-bar

Rick Astley
- Absolutely essential to this project. If your universe does not use the Rick Astley dependency, this will not run on your device.
- The video included is from A.S.T.L.E.Y. found here
  - https://www.youtube.com/watch?v=CotXWxTBIZE
- The GIF included is from Rick Astley's Never Gonna Give You Up
  - https://www.youtube.com/watch?v=dQw4w9WgXcQ
