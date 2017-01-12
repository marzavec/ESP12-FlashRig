# ESP12-FlashRig

After a wholesale purchase of ESP12Fs it became clear that I needed a slick rig for quickly flashing them. Soldering on headers or leads that would need to be removed later was not an ideal use of time. After discarding several crazy ideas, the answer was to simply use pogo pins. Adafruit gave the suggestion to use a 2mm pitch idc cable with the pogo pins pressed in. Foolishly I decided to give the idea a try (see version 1 in build log).


The build then evolved to what you see below; a sturdy 3d printed frame, housing the leads from the pogo pins into an idc cable that can easilty be either adapter to a breadboard or plugged into a pcb built for flashing.


![The Final Form](http://img.marzavec.com/ESP12-FlashRig-12-2.jpg "See hooked up final build at the end of the build log.")



## Circuit / Flashing

For a rough overview of the circuit and how to flash see:

http://www.instructables.com/id/Getting-Started-with-the-ESP8266-ESP-12/?ALLSTEPS

For some slightly more indepth info see:

https://riktronics.wordpress.com/2016/10/19/flash-at-firmware-to-esp8266-wifi-module-easiest-way/

## Usage

Step 1: Print stl.

The stl file available in this git is optimized for .5mm heads. The prints with this sized head fit together perfectly with minimal cleanup.


Step 2: Assemble & Wire up.

I used 2 x 2mm pitch 2x12 24 pin flat IDC ribbon cable. Disassemble one cable & remove the headers from the wire. These headers are then cut down to 8x2 & used to keep the pogo pins aligned. They fit horizontally at the top of the rig.

## Build Log

![Version 1 Start](http://img.marzavec.com/ESP12-FlashRig-1-2.jpg "amidoingitrite-2.jpg")


![Version 1 Ready](http://img.marzavec.com/ESP12-FlashRig-3-2.jpg "Aligned using lab grade popsicle stick lyka pro")


![Version 1 Wiring](http://img.marzavec.com/ESP12-FlashRig-4-2.jpg "Testing continuity with 3d printed brace")


![Version 1 Final](http://img.marzavec.com/ESP12-FlashRig-5-2.jpg "Successful flash & test!")


![Version 2 Start](http://img.marzavec.com/ESP12-FlashRig-6-2.jpg "Started version 2 after the 3d printed brace wore out- this is a much better prototype")


![Version 2 View](http://img.marzavec.com/ESP12-FlashRig-7-2.jpg "You can see the concept of how things will be wired in the end")


![Version 2 Print](http://img.marzavec.com/ESP12-FlashRig-8-2.jpg "Digitalized the version 2 frame, this is the first print")


![Version 2 Point 0](http://img.marzavec.com/ESP12-FlashRig-10-2.jpg "Checked dimensions to make sure everything would fit")


![Version 2 Point 1](http://img.marzavec.com/ESP12-FlashRig-11-2.jpg "Added left and right braces & soldered everything together")


![Version 2 Final](http://img.marzavec.com/ESP12-FlashRig-12-2.jpg "Final design with chip")


![Version 2 Wired up](http://img.marzavec.com/ESP12-FlashRig-13-2.jpg "Final design wired into flashing circuit")


![Version 2 Who am I to argue?](http://img.marzavec.com/ESP12-FlashRig-14-2.jpg "Banana for scale because the internet told me to")


