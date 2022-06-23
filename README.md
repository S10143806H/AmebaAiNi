# AmebaAiNi

## Materials
1. Pot Player: https://daumpotplayer.com/download/
2. Image to TXT converting tool
3. AMB23
4. microSD Card

## Steps
1. Download a video
2. Extract each frame of the video into an image using "Ctrl+G" in potPlayer
3. Covert from image file in to ".txt" file
4. Test: Display ".txt" using a ".html" file in your browser
5. Save the ".html" file into a micro SD card, and insert the SD card into AMB23
6. Download Ameba Arduino SDK from Arduino IDE, replace the ".html" file name in this example: "AmebaFatfsSDIO" -> "read_html_from_SD card"