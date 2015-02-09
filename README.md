#Antdroid Hardware Components
Antdroid is a robot designed to be 3D printed.

It is ***designed in CATIA  V5r21*** with a ***full parametric design***, witch allows you to easily ***resize and adapt*** the model to your own servos or hardware requirements.

Unfortunately, CATIA is not a free opensource program, so if you want to modify it, you will need a license. We would like to port it to a free software solution but, at the moment, it is not posible.


## 3D printable parts
All the parts have been exported to ***stl format***, so you can easily print them.

### Recommendations for printing
| Part             | Layer Height | Infill | Support  | Number of Pieces | Plastic (g) | Material   |
|------------------|--------------|--------|----------|------------------|-------------|------------|
| Coxa             |      0.2     |   40%  |    Yes   |         6        |     189     |     PLA    |
| Femur            |     0.25     |   40%  |    No    |         6        |      30     | PLA or ABS |
| Femur simetria   |     0.25     |   40%  |    No    |         6        |      30     | PLA or ABS |
| Separador        |      0.2     |   40%  |    No    |         6        |      9      |     PLA    |
| Tibia            |      0.2     |   40%  |    Yes   |         6        |     342     |     PLA    |
| Tapa servo       |      0.1     |   50%  |    Yes   |        18        |     128     | PLA or ABS |
| Base inferior    |      0.2     |   25%  |    No    |         1        |     156     |     PLA    |
| Base superior    |      0.2     |   25%  |    No    |         1        |     158     |     PLA    |
| Separador cuerpo |      0.2     |   40%  |    No    |         2        |      19     |     ABS    |
| Soporte camara   |      0.2     |   40%  |    No    |         1        |      20     |     ABS    |
| Pie              |              |        |    Yes   |         6        |             |            |

## Nuts and bolts

| Nuts and bolts            	| Number 	|
|---------------------------	|--------	|
| Countersink screw M2.5x20 	|   13   	|
| Countersink screw M3x16   	|    6   	|
| Screw M3x20               	|   74   	|
| Nut M3                    	|    8   	|
| Washer M3                 	|   18   	|
| Countersink screw 2.2x6.5 	|   72   	|

## Vitamins


| Component                    	| Number 	|
|------------------------------	|--------	|
| Towerpro MG996R 10kg Servo   	|   18   	|
| Lipo Battery (2S or above)   	|    1   	|
| XT60 Connector (Male)        	|    1   	|
| YEP 20A SBEC                 	|    1   	|
| Arduino Mega 2560 r3         	|    1   	|
| Arduino Mega Proto Shield R3 	|    1   	|
| Male Pin Strip 0.1''         	|   60   	|
| DC 7V-24V To DC 5V 3A USB    	|    1   	|
| Raspberry Pi Model B        	|    1   	|
| 8GB SD Card                  	|    1   	|
| USB Wifi                     	|    1   	|
| Raspberry Pi Camera Board    	|    1   	|

***WARN***: To date, Raspberry Pi(RPi) B+ and RPi 2 have been released. Due to design specifications, the ***AntDroid frame can ONLY hold RPi B (NOT model B+)***. This is due to the place of the holes that the RPi board have. In fact, RPi B+ and RPi 2 have more holes (4 instead 2). In future upgrades we are going to fix this problem releasing a base to hold the new RPi. Meanwhile, ***RPi B+ and RPi 2 are not supported***.


Optional

| Component                    	| Number 	|
|------------------------------	|--------	|
| LiPo low voltage alarm        |    1   	|
| PS3 Dualshock controller      |    1   	|
| USB Bluetooth                 |    1   	|
| USB hub external power supply |    1   	|

***WARN***: The SBEC doesn't alert of a low battery charge. It is highly recommendable to add a voltage alarm to the LiPo battery in order to not damage it.

The Raspberry Pi B has only two USB ports. One of them is going to be used by the serial connection with the Arduino MEGA. This fact leaves us two connectivity options:

>Bluetooth
>Wifi

If you want to use them at the same time you will have to buy a USB hub with external power supply because the RPi can not power several devices with a high power consumption.
