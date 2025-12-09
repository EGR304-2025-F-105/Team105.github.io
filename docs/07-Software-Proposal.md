---
title: Software Proposal
---

## Introduction

To determine to whether or not the blinds stay open/close and to further adjust the blind's sliders, the software proposal will showcase the pseudo-coding of how the system will gather information and what to output at the end. The main important goal is too make sure that the product can decide 2 major decisions with the usage of values given by the thermometers. Afterwards, the two actuators will correspond with one another to adjust itself for the comfort of the user.


## Research Question

* How can the PCBs communicate with each other continously without interruption?
* With the two sensors, how can they cooperate with each to ensure the two actuators recieve the signal to move?
* How would the order of boards work to ensure success with the project?

## Images

![Electric Blinds_SProposal](https://raw.githubusercontent.com/EGR304-2025-F-105/Team105.github.io/refs/heads/main/docs/image/Team105_SoProl.drawio.png)

**Figure 1:** UML of an electric blinds that activates the motors by the average temperature of both inside/outside of a home and light value. 


## Results

1. Light and Thermo sensor are able to communicate with one another about when the whole system is on and give values of the temperatures to the actuator.
1. To calculate when the blinds close/open, the motor is looking for the value of zero in the thermo sensor to close itself. However if the temperature within the rang (Value 1), then the decision in the code is whether or not the room is cool enough to keep the blinds open/close. Afterwards, the first actuator communicates to the second to adjust sliders.
1. In total, there should be about 2 major decisions in order for the product to work.

## Conclusions and Future Work

With the proposal, the communication between all four PCBs are visualized to show the internal works of the coding and how it should fuction before the main build. When deciding who goes first, the lgiht sensor was choosen to show how the product turns on/ off to allow the others to function. With that, the two motors are working together to show what happens when the values given by the thermoresistors meet the requirements of the value and while statements. Futhermore, the main sensor that this project is heavily reliant on is the thermoresistor. As shown in Figure 1 above, all major decisions are dependent on the values given by the temperature tracked by the thermoresistor. 

Overall, this proposal shows how the product achieves the requirements on having two sensors and two actuators. Though originally having three sensors, it was decided that having two sensors would make it easier to transfer data as having a third sensor would complicate the product even more.

## Reflections

After the demonstration, there are several changes the could've happen to improve the quality of the project. First, it would be the layout of the coding as it was confusing when trying to put the whole subsystem all together. Though individuality each subsystem worked, there were issues of trying to tell one another about the high/low values. One solution would be further research about the ADC file given by MPLABX to see which code to properly use instead of guessing. 

## External Links

[Software Porposal Draw.io](https://app.diagrams.net/#G1wC5pWVfzkhPJWQpIBmeiUbisRbVUanYt#%7B%22pageId%22%3A%22WzpfuVUmJpjsxw9uIVLz%22%7D)




