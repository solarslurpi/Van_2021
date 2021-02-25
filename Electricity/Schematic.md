![schematic](./images/schematic.png)

_The image is a screenshot of  [a Google Draw document](https://docs.google.com/drawings/d/1X5Fls75ioN82ZMCHzN90oixNZ60E3s5VR6cbR8S1eH8/edit)_.

Six Battle Born 100Ah 12V batteries are connected in parallel providing 600Ah at 12V.  [2/0 Gauge copper wire](https://amzn.to/2Mp7yia) is used to wire the batteries.

The batteries are (re)charged through:
* [solar](Solar.md)
* Shore power (that feeds into the [inverter](inverter.md))

The BMV-712 battery monitor is used to monitor the batteries.

The batteries provide power/electricity to both DC and AC circuits.

It's the AC circuits that "get exciting."  We use [Victrons Multiplus 12/3000/120-50 120v Inverter](inverter.md).

# Wire Size

The size of the wire must:
* Be able to carry the total amount of Amps that the loads will request at one time.
* The amount of resistance must not drop the voltage below what the loads require. _Note: [Nate (explorist.life) recommends at most a 3% voltage drop](https://youtu.be/ki3WXVR48eM?t=110)_.

In Our van:
* The component that draws the most Amps at a time is the inverter.  The biggest current draw occurs when an appliance like a microwave, water heater, or popcorn popper are on.  The cable from the busbar to the inverter is at most 3 feet.
* We will not be running the microwave, water heater, or popcorn popper at the same time.
* The DC loads max at about 7A.  
* The only loads that are on continually are the LED lights, refrigerator (small AC), and components to maintain electricity (like the inverter and the solar battery charger).

We chose [2/0 gauge copper cable](https://amzn.to/2Mp7yia).

![cable between batteries](./images/cable_between_Batteries.jpeg)

![cable to inverter](./images/cable_to_inverter.jpeg)


We chose this size based on:
- We project our largest current draw to be 200A.
- By far the biggest user of current is the inverter.  The cable between the inverter and the busbar is at most 4 feet.  The rest of the current draws are in the 5 - 10A range.  We project at most two of these circuits will be active at one time, adding about 20A.
- The diameter of the cable is easier to work with than 3/0 or 4/0.

![cable size](./images/CurrentFlow_CableSize_SM.png)  

_Note: [Here is a higher resolution image of the cable diagram](./images/CurrentFlow_CableSize_Original.png)_

--TODO: FUSES...WHY THE SIZES THEY ARE AT? Why is there one in the batteries.

