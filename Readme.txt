ARDUINO BLUETOOTH RC CAR (ANDROID CONTROLLED)
Intro: Arduino Bluetooth RC Car (Android Controlled)
Hello, in this project I will show you how to transform an RC toy car to Bluetooth controlled through your Android smartphone!

Before starting, make sure that you have:
Arduino uno board
L293D motor driver
HC-06 Bluetooth module
RC Car that can fit all the above !
Optional you will need:
1M & 100K resistor for battery level
4x leds for lights
1x speaker/buzzer for horn sound
For power, you can use the existing batteries (4x 1.5V AA), or replace them with a LiOn rechargeable battery pack.
(I used 12V LiOn rechargeable battery pack)


Step 1: Remove the Existing Rc Circuit

Before starting, remove the existing rc circuit. You will not need it any more... you will make a better one from the beginning with Arduino uno ;)
Now, with one battery AA 1.5V you must find the polarity of 2 c motors.
For movement motor (back side) the positive polarity cable will be that moves the car forward.
For direction motor (front side) the positive polarity cable will be that moves the wheels left.

Step 2: Breadboard Schematic

Step 3: Code

Download and open file with Arduino ide. Read every line of code (+comments) to understand how it's working and then upload it to your Arduino uno board!
(for programming arduino uno board you must disconnect first the RX & TX pins of Bluetooth module)

First enable Bluetooth and establish connection with BT module. 
(ex. HC-06, password 1234) 
Use "Help & info" button if you can not understand how it is working.

Accelelometer function is under developing, use with attention!

Link app :https://play.google.com/store/apps/details?id=braulio.calle.bluetoothRCcontroller

