# 39c3PCBLEDC100R

The 39c3PCBLEDC100 is a Coaster for your drinks with option for LED and microcontroller upgrade. By stacking the coasters, you can also build nice blinky towers.



## Rev.0

### Electrical connections

Important: Do not power the board by USB and an external power supply at the same time!
The Din pin of the first LED is connected to pin D4 (GPIO2) of the Wemos D1 mini. ...well, not directly: there is a MOS-FET Transistor in between to shift the signal level from 3.3V to 5V. 
Two of the mounting holes are connected to GND, two of the holes are connected to 5V. You can use this feature to stack multiple 39c3PCBLEDc100R Boards with brass spacers.

The button is connected to D3 (GPIO0) and GND. In WLED (Time & Macros -> Button actions) you can configure actions for short, long and double click.

## License
    
39c3PCBLEDC100R © 2025 by c3RE is licensed under CC BY 4.0. To view a copy of this license,   
visit http://creativecommons.org/licenses/by/4.0/


