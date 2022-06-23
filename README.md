# Ameba Play AiNi using TXT

![Cover](https://scontent.fsin15-1.fna.fbcdn.net/v/t39.30808-6/289649271_1831959893666041_751678281649482315_n.jpg?_nc_cat=108&ccb=1-7&_nc_sid=5cd70e&_nc_ohc=zuPjCJC3tW0AX9hY1N_&_nc_ht=scontent.fsin15-1.fna&oh=00_AT92sEoEnd9bbqNEfmdUOF7uYNxA01-1FdrW8JEqCuIE3w&oe=62B8E0C1)

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
