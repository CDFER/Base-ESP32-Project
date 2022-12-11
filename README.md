# Base ESP32 Project (under development)

Based on my captive portal example but with RTOS, LittleFS and a basic webserver with chart.js

When you connect to the wifi "captive" password "12345678" it should take you straight to <http://4.3.2.1/> and display some graphs.


## Known Warnings showing up with current version

- [AsyncTCP.cpp:969] _poll(): rx timeout 4
- [AsyncTCP.cpp:949] _poll(): pcb is NULL

### Further testing required

- Library Versions

### Future Dev Options to look into (Help or suggestions are appreciated)

- OTA Updates
- Log files
