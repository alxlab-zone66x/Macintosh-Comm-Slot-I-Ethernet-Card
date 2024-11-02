# Macintosh Comm Slot I Ethernet Card

This is a recreation of Macintosh Comm Slot I Ethernet Cards based on the Farallon EtherMac LC Comm Slot Ethernet Card.

The card is based around the LAN91C94 or LAN91C96 ethernet controller. 

An AT93C46 128KB serial EEPROM in **16 bit mode** is used to store configs. There's a dual footprint so either the DIP or SOIC version of the chip can be used. Don't use an 8 bit only version of this chip.

A 16V8 PLD is used. The v1.2D uses a DIP package and rest use PLCC package.



### v1.0 Notes

This version is a direct recreation of the Farallon card. I had JLCPCB assemble some boards but I wasn't able to get it to work. Not exactly sure what the problem is. Maybe some of the components I source from Aliexpress are no good.

### v1.1 Notes

This version is a slight tweak of the original Farallon card with space added for PLCC sockets and some through-hole components switch to SMD. This is untested.

### v1.2 Notes

Version 1.2 simplifies the Farallon card's design by removing the thinnet components. The RJ45 jack was replaced with a jack that has built in magnetics and LEDs for link and activity.

#### v1.2

This variant is made for a PLCC-20 SMD socket for the 16V8. Untested.

#### v1.2P

This variant is made for a PLCC-20 TH socket for the the 16V8. Tested and working except for the activity LED.

#### v1.2D

This variant is made for a DIP-20 socket for the the 16V8. Tested and working except for the activity LED.







## License

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a>

[Macintosh Comm Slot I Ethernet Card](https://github.com/alxlab-zone66x/Macintosh-Comm-Slot-I-Ethernet-Card) © 2024   by  [ Alexandre Marcoux ](https://www.alxlab.com) is licensed under [ Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International](https://creativecommons.org/licenses/by-nc-sa/4.0/?ref=chooser-v1)



## Community

For more great retro hardware projects and a great community check out:

[<img src="docs\tinker_different_sat_rev_600.png" alt="Tinker Different" style="float: left;" />](https://tinkerdifferent.com/)









Join us in #TinkerDifferent on [Discord](https://discord.gg/GrKnnNmt) to help make retro solutions available to all.

[<img src="docs\discordbanner.png" alt="Discord TinkerDifferent" style="float: left;" />](https://discord.gg/GrKnnNmt)





