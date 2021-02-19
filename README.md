# reflow-ioboard-hw
A general purpouse microcontroller board with electronics to read a pt1000 up to 300°C

# why this was designed
This board was designed to modify a genric small oven to reflow solder in it. 
The whole idea behind it was to make a very fancy reflow oven, where the UI and controlling is managed by a RPI with a touchscreen.
To Interface with a RPI there is a I2C Port on the side (the PI should also power the board via 3,3V. Yet the relays should be powerd via a 5V powersupply).
It feauters 3 screwterminals dedicated to drive relays (mosfet, no driver), 2 leds and some IO Ports.

I used a Heraeus Nexensos W-EYK 6 PT1000 aus PT1000. (Conrad Art Nr: 000172430)
Eventually you have to recalulate the resitors for the amplifier.

Yet you can use this board for many different applications.


# wirining

I hope the labeling on the board are clear enough


# software
To this day the software hasn't been implemented. If it works I will put it in a different repository.

# assembling
To assemble this board reflow soldering is adviced. (How Ironic)
I used maker paste, a stencil and a pan and some screws.



I hope this project helps you.
You are free to use it.
You are free to modify it.

Please Note: This is a project I done private, so don't expect it to be beuatiful :P

Sorry for my bad english, I'm hungry :P

If you want to support my Projects: Here is a link to Aisler where you can order the PCB (Warning: Diodes and Mosfet are not assigned):
https://aisler.net/p/IZKNMKIW

