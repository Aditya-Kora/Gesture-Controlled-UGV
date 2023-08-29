# Gesture-Controlled-UGV
This project is about the gesture Controlled unmanned ground vehicle where I used raspberry pi, esp 32, motor controller
I have used raspberry pi with opencv module installed in it and used it to detect my hands and count the number of fingers and deprnding on the number of fingers i will be sending the message to esp 32 to either move the car front, back, left or right
To send the the message from Rpi to Esp 32 i will be setting up my Rpi as mosquitto broker server and my esp 32 as subscriber so it can recive the messages sent by my server
And finally using the messages recived by esp32 will be used to control the motors and move our vehicle according to the messages with the help of motor driver 
