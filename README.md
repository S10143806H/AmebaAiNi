# AmebaAiNi

![Cover]()

## Materials
1. [Pot Player](https://daumpotplayer.com/download/)
2. Image to TXT converting tool
3. [AMB23 Dev Board](https://www.seeedstudio.com/Ameba-RTL8722DM-mini-EVB-Arduino-WiFi-Shield-p-5055.html)
4. microSD Card

## Steps
1. Download a short video
2. Extract each frame of the video into an image using "Ctrl+G" in Pot Player
3. Covert from image file in to ".txt" file using the tool in `tools` folder
4. Test: Display ".txt" using a ".html" file in your PC browser
5. Save the ".html" file into a micro SD card, and insert the SD card into AMB23
6. Download Ameba Arduino SDK from Arduino IDE, replace the ".html" file name in this example: `"AmebaFatfsSDIO" -> "read_html_from_SD card"`
