---
title: Component Selection Example
---

**Moisture Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br>Option 1.<br> 4411-ST0160-ND CAPACITIVE SOIL MOISTURE SENSOR<br>$1.89/each<br>[link to product](https://www.digikey.com/en/products/detail/sunfounder/ST0160/22116813)                 | \* Inexpensive<br>\* Analog voltage output<br>\* Great corrosion resistance                                               | \*  Temperature sensitivity<br>\* Slow response to rapid moisture changes<br> |
| ![](image3.png)<br>\* Option 2. <br>\* 1528-2753-ND STEMMA SOIL SENSOR - I2C CAPACIT <br>\* $1/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4026/9745252) | \* Uses I²C communication <br>\* Great corrosion resistance <br> \* Built in temperature sensor for calibration | * More expensive                                                          |

**Choice:** 4411-ST0160-ND CAPACITIVE SOIL MOISTURE SENSOR

**Rationale:** The 4411-ST0160-ND capacitive soil moisture sensor provides excellent corrosion resistance, is relatively inexpensive when purchased from the correct retailer, and outputs the analog signal required for my analog circuit.


**Op Amp**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image2.png)<br>Option 1.<br> MCP6004 Op-Amp <br>$0.60/each<br>[link to product](https://www.digikey.com/en/products/detail/microchip-technology/MCP6004-I-P/523060)                 | \* Low power consumption per amp 100uA    <br>\* Easy mounting <br>\* Four op amp systems in one                                               | \*  1.8-6V limited supply range<br>\* Lower bandwidth of 1MHz<br>\*Low slew rate of 0.6 V/us |
| ![](image4.png)<br>\* Option 2. <br>\* BH26AASF BATTERY HOLDER AA 6 CELL SNAP <br>\* $2.44/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/mpd-memory-protection-devices/BH26AASF/470766) | \*  <br>\* Wide supply range of 3-36v <br> \* EMI and RF filtering | * Uses more power per amp 300 uA<br>\* Two op amp system                                                          |

**Choice:** MCP6004 Op-Amp

**Rationale:** The MCP6004 op-amp is a component I am already familiar with and provides reliable readings. It also meets the requirements of my 5-volt circuit.


**Power supply**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image5.png)<br>Option 1.<br> 237-1427 AC/DC WALL MOUNT ADAPTER 9V <br>$15.48/each<br>[link to product](https://www.digikey.com/en/products/detail/triad-magnetics/WSU090-2500/3094953)                 | \* Sufficient power output 9V-2.5A    <br>\* Long cord <br>\* Plug in and forget                                               | \*  High cost<br>\* Requires outlet socket<br>\*Requires voltage regulator |
| ![](image6.png)<br>\* Option 2. <br>\* 237-1427 AC/DC WALL MOUNT ADAPTER 9V <br>\* $2.44/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/mpd-memory-protection-devices/BH26AASF/470766) | \* Cheap <br>\* Increases portability <br>\* Doesn't require a wall socket | *Requires battery swapping   <br>\* Introduces energy capacity <br>\* Battery depletion may affect circuit                                                          |

**Choice:** 237-1427 AC/DC WALL MOUNT ADAPTER 9V

**Rationale:** The AC/DC wall mount adapter provides a constant power source for long-term use and supplies sufficient power for the circuitry. A voltage regulator is required to reduce the output voltage to 5 V to safely power the other components.


