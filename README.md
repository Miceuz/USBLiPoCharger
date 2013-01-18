USBLiPoCharger
==============

LiPo / Li-Ion chargers based on MAX1555, MAX1551 and MCP73831. 

Features: 
 - home PCB manufacturing friendly
 - selectable USB/external DC power source - if you don't need USB, just chop off the connector and use DC pads
 - for MAX155X parts - charging current selectable by solder jumper
 - for MAX1555 and MCP73831 - charging and battery full indication LEDS; Note: MAX1555 charger indication relies on low mosfet gate threshold voltage - below (5V - Vfwdled), I've used 702 mosfets.
 - for MCP7383 - charging current selectable by two resistors
