# FBV2MIDI
Use Line6 FBV to control different amps with the help of an Arduino Board.

I want to use the FBV longboard with a Vox AD120VT. 

Both units have a proprietary data protocol.
I alrady analysed the Vox some time ago.
No i analyse the Line6 FBV.
At the moment i can interpret each key an pedal informatin from the FBV.
Also i can set the status of each LED.
What is missing is the display which i will have done soon.

As i am not so good with C++, i am looking for contributors who can make a class for the Fbv and one for the vox.
The classes should have a constructor with a parameter which serial port to use (hardware/software)
and callback routines for keypressed, key-released, control changed, etc....

I will add the analysed values the next days.



