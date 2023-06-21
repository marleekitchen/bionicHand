# bionicHand

Arduino code that implements the basic functionalities of a 3D printed hand.

## How it Works

### Button1

When pressed, triggers the closeThumb() function that closes the thumb. Meant for grasping small objects, can grab delicate items due to integration of a force sensor.

### Button2

Triggers the closeHand() function to close all of the fingers in order to grab larger items. The stopping point of the closed fingers can be altered by changing either or both of the thumb_threshold and rem_threshold variables.

### Button3

Pressing this button causes the openHand() function to be triggered, opening the hand to its resting position.

![IMG_3933 (1)](https://github.com/marleekitchen/bionicHand/assets/104484519/3d27cee2-0c28-4469-b50b-4e8b63bfa191)
![IMG_5784](https://github.com/marleekitchen/bionicHand/assets/104484519/bc979ece-843e-4a0e-849c-57c8cfcaf987)
![IMG_5788](https://github.com/marleekitchen/bionicHand/assets/104484519/6a33c3d9-bafd-40fb-9ab5-194acf2c4aa3)
https://github.com/marleekitchen/bionicHand/assets/104484519/314dd961-163c-4a30-ae7c-9a0e8c1f0b17
