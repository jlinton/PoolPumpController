# PoolPumpController
AVR based multispeed pump controller/timer for pools. With windows .NET scheduling UI, and schematic layouts for hardware.

My old house had a pool. In order to save some energy I replaced the pool pump motor with a multispeed motor. The idea was to filter the water with one of the low speeds. Then for an hour or so run the pump at high speed to power the cleaning vacuum. I also wanted a freeze guard, and eventually some more advanced functions (chemical feeder, separate valve controls for the hot tub and pool, etc). Nothing on the market at the time really fit what I wanted to do, so I started prototyping a device to meet my requirements. 

This code and the associated hardware powered my pool with a 2.5 HP motor (lots of current) for the better part of four years. I finally simplified the whole thing back to a freeze guard timer and a single speed pump. What I learned is that designing electronics for extended temperature (180F to -20F) enclosed in a waterproof box sitting in the sun isn’t for the feint of heart, or someone with kids, and dozens of other projects. And, yes the temp sensor in the box recorded temps in the 140-150’s with regularity. 

I will eventually upload most of the related files, but for starters the plan is to provide the code running on the AVR which is written in C has a simple text UI for an LCD and a 5 direction joystick. 
