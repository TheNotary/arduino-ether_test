## Ether Test

This is a test of a 3rd party library and an ethernet module.  


## To Deploy

    $ git clone https://github.com/TheNotary/ether_test
    $ cd ether_test
    # modify src/ether_test.ino so IP Address works on home network
    # connect Arduino Uno to dev machine
    $ platformio run

    # Unplug Arduino Uno from dev machine
    # Plug Arduino into home network
    # Power the Arduino Uno

    # ping 192.168.0.200
    # do http get request to address
    

## Parts

ENC28J60 - Network module with SPI interface (ebay) (HR911105A?)

Arduino Uno - Microcontroller

~12v DC @ 1amp power adapter

Ethernet cable

A standard, run of the mill, home ethernet network.

Computer that can ping and has a web browser

## Wiring

The board to board interface used is SPI, utilizing 6 wires including ground.  

(Ethernet Pins - Yours may differ)
```
pin 1: CLK
pin 2: INT
pin 3: WOL
pin 4: SO
pin 5: SI
pin 6: SCK
pin 7: CS
pin 8: RST
pin 9:  VCC (3 or 5v)
pin 10: GND
```

(Arduino Uno Pins)
[Arduino Uno Pins](http://www.electroschematics.com/wp-content/uploads/2013/01/Arduino-Uno-R3-Pinouts.png)

(Ethernet -> Arduino Uno)
```
SO  -> pin 12
SI  -> pin 11
SCK -> pin 13
CS  -> pin 8
VCC -> 3.3v
GND -> GND
```

## Resources

[tut](http://nathanhein.com/2013/02/getting-arduino-online-with-an-enc28j60/)

