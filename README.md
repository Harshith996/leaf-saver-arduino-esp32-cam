# leaf-saver-arduino-esp32-cam
This is the second part of [this projsct](https://github.com/Harshith996/leaf-saver-server/blob/main/README.md). The first part consisted of the server side code for the AI processing. This part aims at capturing the images of the leaves to be sent to the server. For this project, I used an ESP32-Cam AI-Thinker module. Since it does not have a USB port, I needed to use an FTDI board to program the module. This is the [schematic of the connections](https://i1.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/12/ESP32-CAM-FTDI-programmer-5V-supply.png?w=750&ssl=1). After making the connections, use the code in the repository to get the cam working. Make sure to replace the IP address of the server, the SSID and Password of your Wi-fi and the image capture frequency as per convenience.
