# CD-160
Lenoxx Sound CD-160

Project to repair and reverse engineer the Lenoxx Sound CD-160 boombox.

The goals:
* Repair the radio functionality
* Replace belts on the tape decks to get it working agian
* Add AUX and Bluetooth

The last goal is the one adding the requirement of doing some reverse engineering. The idea is to integrate the new feature as much as possible within what's existing, making it a seamless integration. I've discovered that the onboard SoC (TC9309AF-119) and Mux chip (TC4052BP) already support a 4th input not currently implemented by the boombox. Using that 4th input currently disconnected should enable seamless integration and selection of a AUX audio source on which to connect our new AUX and Bluetooth module.

Videos are also being recorded of the process, hopefully to be uploaded to YouTube at a later date.
