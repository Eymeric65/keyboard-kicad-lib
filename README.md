# keyboard-kicad-lib

Please if you find this repository usefull don't hesitate to **share it**, **star it**, **check my blog** and **consider giving me a tiny tip on paypal** *(I am a broke student that put all his monney toward electronics)*.


This is the official repository for the **easy keyboard kicad library**.
This library has been made in order to lower the skill ceiling for keyboard development.

The library has been used to create the [Tokei keyboard] and the [hillside speedrun]. Feel free to send me a mail or a DM in order that I add your creation to the list !! 

## How to use the library

So this is a *normal* kicad library. For the main part you can make the keyboard using this library totally normally.
The best part is when creating the 3D shell of the keyboard, every footprint has special feature in order to streamline the creation of the 3d printed part. Here is a little summary : 
- **Edge.cuts :** The board edge cut, used like in any other electronic project, However got also the cut for the battery
- **User.Drawings :** User drawing show the Keycap U-rectangle, it is used in order to make the *Edge.custs* of the board
- **User.1 :** The first User layer, is used for *key supporter* in the **top cover plate**.
- **User.2 :** The second User layer, is used for *bottom cover space holder* in the **bottom cover plate**. (it is the bottom space for component...)
- **User.3 :** The third User layer, is used for *key and mount hole* in the **top cover plate**.
- **User.4 :** The fourth User layer, is used for *mount and utilitary hole* in the **bottom cover plate**

In addition, every footprint is totally reversible, so after making the 3D part you can simply mirror the keyboard in order to get the other half.


## Library component detail

In this section I will detail every componenet of the library. 

### Schematic

| title | schematic image | comment |
|:-----:|:---------------:|:-------:|
|Keyboard push |![Keyboard push schematic](images/keyboard_push_schematic.png) | the base schematic for the push button and the diode |
| Battery no pin |![Battery no pin schematic](images/battery_no_pin_schematic.png) | schematic for the battery without any pin (for hole purpose) |
| NRF micro jumper | ![NRF micro jumper schematic](images/NRF_micro_jumper_schematic.png) | NRF micro schematic for the reversible footprint | 
| NRF micro *legacy* | ![NRF micro schematic](images/NRF_micro_schematic.png) | For legacy purpose, compatible with old footprint | 


### Footprint

| title | footprint image | 3D model image | comment |
|:-----:|:---------------:|:--------------:|:-------:|

## Keyboard speedrunning

For more information about Keyboard speedrunning please check here

## Keyboard made thanks to this repository

don't hesitate to reach me in order that I cite you back here ! *(you can also ask for a merge request)*



## Contribution

The main contributor is Eymeric CHAUCHAT.
blog : [chauquest.com](chauquest.com)