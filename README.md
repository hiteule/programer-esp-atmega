# ESP / Atmega programmer

An electronic board designed to programm an ESP or an Atmega microcontroller.
The board is based on a FT32RL Serial Adapter module.

You need to switch the JP-RTS jumper to be able to programm the ESP or the Atmega.
You need to switch the voltage level of the Serial Adapter module to programm the ESP (3.3V) or the Atmega (5V).

The 3.3V power output of the Serial Adapter module is too weak to run the ESP.
You need to use an external power source between 3.3V and 12V through J1.
The Atmega is not concerned (powered through the USB / Serial Adapter module).

The card was designed with [Eagle].
The additional [libraries] used are:
* CONNECTORS.lbr
* regulator.lbr

[Eagle]:     https://www.autodesk.fr/products/eagle
[libraries]: https://github.com/hiteule/eagle-library
