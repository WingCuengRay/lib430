# MSP430 Code Library #

This Google code location is meant as a library source for Texas Intruments' MSP430 Microcontrollers.

It starts out especially with code for devices on the Launchpad and C language.
I have most of the code for the devices and modules on the ToDo list in Assembly language but I thnik it's much more flexible to make them available in C too.
Im also working on a booster pack for the Lauchpad containing most of the sensors.

  * [ToDo List](ToDo.md)
  * [Projects](PrjDocu.md)

```
                                      MSP430G2230
                              /|\  -----------------
                               |  |                 |
                               ---|DVCC         DVSS|--|
                                  |                 |
                                 -|P1.2          TST|-
                                  |                 |
                                 -|P1.5          RST|-
                                  |                 |
                                 -|P1.6         P1.7|-
                                  |                 |
                                   -----------------
```


