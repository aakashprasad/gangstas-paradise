Gangsta's Paradise
This code is based on

## Hardware

Just connect an piezo to the board and you are good to go. Pin 11 is used in every sketch because some piezo speakers can be connected between it and the close GND pin without any wiring. You can use basically any pin, as long  as they can be used as digital pins (pins A6 and A7 of the Arduino Nano and mini are analog only). Just remember to assign the pin number to the `buzzer` variable. 

![alt tag](hardware.png)

There are two kinds of piezo buzzers: active and passive. The active one that plays a specific pitch when powevered and is not good for this purpose. The passive kind functions like a speaker, reproducing the pitch you apply to it. You can test the piezo speaker with the "blink" example, the good piezo speaker will just click, while the other kind will play a pitch every other second.  

