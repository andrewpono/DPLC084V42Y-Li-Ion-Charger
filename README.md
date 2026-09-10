# DPLC084V42Y-Li-Ion-Charger
42V 2A Li-Ion Charger for 36V E-Bike, Scooter battery. Not the bottom of the barrel junk, but still undercooked.<br>
![](/Images/charger.png)<br>
Charger [reverse engineered](DPLC084V42Y.pdf) to reduce both output voltage and current. At default current (a bit under 2A) the charger gets pretty hot, transformer core temperature measured in open air is about 60C, heatsinks hover around 50C. Enclosed it will get much hotter. Lowering current drops the temp by about 10C in open air. Lowering output voltage by 0.5-1V prolongs the battery life.
- To reduce the current, solder 2k resistor in parallel to R40. Resulting current is about 1.3A.
- To reduce the voltage, adjust the VR pot.

The unused IC6B op amp is left unconnected, not a good idea, even though it does appear to oscillate at the time of this test. Short C19 and R18 to make it safe.<br>
Hot side part may contain errors, cold side should be pretty accurate.
