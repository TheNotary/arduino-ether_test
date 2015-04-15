## Ether Test

This is a test of me using a 3rd party library and an ethernet module.  


## To Deploy

    $ git clone this-repo
    $ cd ether_test
    # modify src/ether_test.ino so IP Address works on home network
    # connect Arduino Uno to dev machine
    $ platformio run

    # Unplug Arduino Uno from dev machine
    # Plug Arduino into home network
    # Power the Arduino Uno

    # ping 192.168.0.200
    # do http get request to address
    

## Equipment

ENC28J60 - Network module with SPI interface

Arduino Uno - Microcontroller

12v DC @ 1amp power adapter

Ethernet cable

A standard, run of the mill, home ethernet network.


## Resources

[tut](http://nathanhein.com/2013/02/getting-arduino-online-with-an-enc28j60/)
[Arduino Uno Pins](http://www.electroschematics.com/wp-content/uploads/2013/01/Arduino-Uno-R3-Pinouts.png)


