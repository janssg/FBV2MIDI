

class VoxAd60Vt is used for the communication between the VOX AD60VT and the arduino Board


line6Fbv2VoxAd60Vt.ino lets the FBV control the VOX

it currently has a few minor bugs with switching the tuner.


Functionallity:
   - Amp1, Amp2 + Pdl1 Switches activate the Pedal Stomp Box (Wah etc.)
   - Modulation, Reverb Delay and Tap use the corresponding switches
   - FX Loop = Tuner
   - Stomp 1 = Tuner silent
   - Bank up/down and Channel A-D are used to select the Programs

   - as a special feature i made a Wah auto on/off function
   if the Effect is off by default in teh preset, the auto mode is activated.
   When the Pedal is moved, the effect is automatically switched on
   and after 0,7 seconds of no movement it is turned off again
   StompBox 3 indicates and switches this mode

this Folder contains an earlier Version of the line6 FBV Library.
The ino file is not adapted to the latest version of the FBV libtrary found in the LINE6FBV folder.






