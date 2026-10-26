---
title: Component Selection Example
---

## Examples

### Style 1

> This is the example found in the assignment, uses more html

*Table 1: Example component selection*

**Moisture Sensor**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](image1.png)<br>Option 1.<br> 4411-ST0160-ND CAPACITIVE SOIL MOISTURE SENSOR<br>$1.89/each<br>[link to product](https://www.digikey.com/en/products/detail/sunfounder/ST0160/22116813)                 | \* Inexpensive<br>\* Analog voltage output<br>\* Great corrosion resistance                                               | \*  Temperature sensitivity<br>\* Slow response to rapid moisture changes<br> |
| ![](image3.png)<br>\* Option 2. <br>\* 1528-2753-ND STEMMA SOIL SENSOR - I2C CAPACIT <br>\* $1/each <br>\* [Link to product](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4026/9745252) | \* Uses I²C communication <br>\* Great corrosion resistance <br> \* Built in temperature sensor for calibration | * More expensive                                                          |

**Choice:** 4411-ST0160-ND CAPACITIVE SOIL MOISTURE SENSOR

**Rationale:** The 4411-ST0160-ND capacitive soil moisture sensor provides excellent corrosion resistance, is relatively inexpensive when purchased from the correct retailer, and outputs the analog signal required for my analog circuit.



### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.
