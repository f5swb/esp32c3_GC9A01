# ESP32c3_GC9A01
a script to run esp32c3 SEED XIAO with GC9A01 eye animated gif

First of all you have to downgrade the esp32 lib to 2.0.14 version into the arduino IDE, if not the screen will not light !
Not yet tested with higher lib versions ...

librairies used :
- esp32 v 2.0.14
- TFT_eSPI 
- Animated GIF

Go to https://github.com/thelastoutpostworkshop/animated_gif_memory to download the original prog

Go into /Documents/Arduino/libraries/TFT_eSPI and rename User_Setup.h to User_Setup.save
then copy the file User_Setup.h in this repository this is the config to drive correctly the screen with the esp32c3 according to my schémas.png !

Then copy the file my eyes animated_gif_memory script in the /images directory

then compile :)

