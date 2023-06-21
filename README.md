# bionicHand

Arduino code that implements the basic functionalities of a 3D printed hand.

## How it Works

### Button1

When pressed, triggers the closeThumb() function that closes the thumb. Meant for grasping small objects, can grab delicate items due to integration of a force sensor.

### Button2

Triggers the closeHand() function to close all of the fingers in order to grab larger items. The stopping point of the closed fingers can be altered by changing either or both of the index_full_threshold and rem_full_threshold variables.

### Button3

Pressing this button causes the openHand() function to be triggered, opening the hand to its resting position.
