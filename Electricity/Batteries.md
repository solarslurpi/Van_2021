# Batteries
We have installed 6 Battle Born 12V 100Ah batteries.  The 6 batteries are connected in [parallel](https://en.wikipedia.org/wiki/Series_and_parallel_circuits).  

## Output
Our system outputs 12V DC Power at a capacity of 600Ah.

![batteries](./images/batteries.png)

## Charging
The batteries are charged by either:
* [Solar](Solar.md)
* On Shore
### State of Charge
We installed Victron's [BMV-712 - Battery Monitor](https://battlebornbatteries.com/faq-all-about-bmvs/).  As noted in Victron's ["Energy Unlimited"](./documents/Book-Energy-Unlimited-EN.pdf) document: 

```
A battery monitor keeps track of the current flowing in and out of the battery. Integration of this current over time (which if the current would be a fixed amount of amps, boils down to multiplying current and time) gives the amount of amp-hours flowing in or out of the battery. For example: a discharge current of 10 A for 2 hours means that the battery has been discharged by
10 x 2 = 20 Ah.
```
...__To calculate Ah charge or discharge of a battery, a battery monitor only makes use of current and time__
