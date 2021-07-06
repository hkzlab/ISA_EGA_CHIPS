# Enhanced Graphics Adapter

## Introduction

This board is based on a reversed **PA-WTEGA** card, based on the **CHIPS** chipset (P82C435 + P82A436). 

![EGA CHIPS](pics/isa_ega.jpg)

### Disclaimer

I take NO responsibility for what happens if you decide to build and use this card. Your computer might crash, catch fire or be destroyed in other nasty ways.
You're encourauged to take what you deem fit from this, and use it in your projects!

### Functionalities

✅ means I tested the functionality and it works, ❌ means I tested the functionality and found issues, ? means that the functionality has yet to be tested.

* [✅] Display checkup with CheckIt
* [?] Feature Connector
* [?] Light pen input

## Bill of Materials

| Component         | Qty | Type / Value        |
| ----------------- | --- | ------------------- |
| **TODO**          |     |                     |

### BIOS

Testing for Phoenix Video Bios V1.02 for P82C435.

### Component substitutions

* U15 and U13 can be substituted with HCT equivalents
* U4 is an 'LS244 in the original card, I noticed an improvement in image stability by using an 'F244

## Known issues

### Rev 0.1

* ?

### Rev 0

* Some traces stub are left near the edge connector
* Some traces for sensitive sync signals are routed under the oscillators

## TODO

* ???

## Credits

Thanks to [Sergey Kiselev](https://github.com/skiselev) for his symbol/footprint library!

