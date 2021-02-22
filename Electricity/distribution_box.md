# Distribution Box
The distribution box manages the DC and AC circuits.  We have the [Arterra WF-8930/50NPB distribution "center"](https://wfcoelectronics.com/wp-content/uploads/2019/06/8930-50-Series-Manual-FINAL-web.pdf).
![distribution box](./images/distribution_box.jpeg)

Here's an image of their wiring diagram.
![distribution wiring](./images/distribution_wiring.png)

## DC Circuits
The DC part is pretty easy.  The challenging part might be deciding what Fuses to use.  Our box has the following DC circuits:

## AC Circuits
The wiring diagram has "30A Shore cord" coming into the 30 A main breaker.  Our "cord" is the AC OUT from the [inverter](inverter.md) (i.e.: AC OUT from the inverter is AC in for the distribution box).  Now that we have AC IN, we can start wiring the other circuits.  

The main breaker is a 30A SQUARE-D HOM One-Pole circuit breaker.  We use SQUARE-D HOM TANDEM circuit breakers for the AC circuits to the Van's appliances.  This way, we can have up to six AC circuits.

![AC wiring](./images/AC_wiring.jpeg)


Our AC Circuits - starting to the left of the 30A Circuit Breaker:
* First Circuit Breaker:
    * 15A connected to the built-in outlet on the back of the Panel.
    * 15A connected to the plugs behind the seats in the "Living Room".
* Second Circuit Breaker:
    * 15A connected to the plugs in the Kitchen cabinet where the pots and pans are stored.
    * 15A connected to the plugs used by the microwave and fridge.
* Third Circuit Breaker:
    * 20A is not used.
    * 15A connected to the plug used by the water heater.