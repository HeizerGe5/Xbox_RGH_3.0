Xbox 360 RGH3 by 15432 v 1.0

Features list:
- CPU glitch from the SMC code
- Two wires setup, no chip required
- HANA PLL bypass + CPU PLL bypass slowdown
- Immediate restart on unsuccessfull glitch (1 sec per cycle)

Wiring, Corona:
- CPU_PLL_BYPASS -> DB3R4
- POST_BUS_1 -> DB3R3

Wiring, Trinity:
- CPU_PLL_BYPASS -> DB2G3 (1-10k safety resistor recommended!)
- POST_BUS_1 -> R3R19

Wiring, Jasper / Falcon:
- CPU_PLL_BYPASS -> DB1F1 (1-10k safety resistor recommended!)
- POST_BUS_1 -> R3P7

Known Jasper/Falcon issues:
- HANA PLL bypass slowdown is not enough for perfect precision,
but HANA PLL reconfig slowdown is unstable. So there are two
files for both ways to try.
- Some consoles crash and never boot because of PLL slowdown, please use RGH2 there

Other known issues:
- Falcon, Jasper & Trinity wiring on retail SMC results in RRoD.

Contacts, PayPal donates: 15432@mail.ru