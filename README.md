# ESE-5190_Lab_2B

LAB 2B Expansion Board Proposal

# Plan Outline

This program aims to light 2 different LEDs based on the character input by the user. On pressing the key " C " , the green LED starts blinking , and the blue LED blinks upon pressing the key " D". The ```SCL1``` pin of the **QTPy RP2040** is connected to the ```GPIO23``` pin and the ```SDA1``` pin is connected to the ```GPIO22``` pin.  We set the ```GPIO``` direction to out using ```gpio_set_dir``` and initialise the ```GPIO``` pins 22 and 23. The user input is read by using **getchar_timeout_us** which accepts a single character.

<br>

This image is a representation of the pins present on the ```QTPy RP2040```.

![EMBEDDED_LED_GPIO](https://user-images.githubusercontent.com/114244849/197115827-759bb061-b5e9-46da-9400-969947c56cb4.JPG)


## COMPONENTS USED:
- Breadboard
- LEDs( Blue and green)
- Resistors( 1K Ohm and 100 Ohm)
- RP2040 Microcontroller
- STEMMA QT Cable



# Video of the Implementation


https://user-images.githubusercontent.com/114244849/197117757-3a9099ad-195a-41f0-aa6b-6f4df895a128.mp4



