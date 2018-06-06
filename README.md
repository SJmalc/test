### Arduino libraries necessary for PottyHub:
- AzureIoTHub
- AzureIoTHubMQTTClient
- AzureIoTProtocol_Http
- AzureIoTProtocol_MQTT
- AzureIoTUtility
- Bridge

### To set up ESP8266 Board in Arduino:
1. Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into Additional Board Manager URLs field in Arduino's preferences tab.

2. Use Board manager (found in Tools-->Board-->Board Manager) to install ESP8266 package.

  - now you can select "Adafruit Feather HUZZAH ESP8266" in the Board tab

3. Set 80 MHz as CPU frequency, 115200 baud upload speed, and select matching COM/serial port for cable.
