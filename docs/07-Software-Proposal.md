---
title: Software Proposal
---

## Introduction

To determine to whether or not the blinds stay open/close and to further adjust the blind's sliders, the software proposal will showcase the pseudo-coding of how the system will gather information and what to output at the end. The main important goal is too make sure that the actuator can close/open the blinds with the values recieved from the IR Emitter which is functioned by both the light and thermoresistor sensors.


## Research Question

* How can the PCBs communicate with each other continously without interruption?
* With the two sensors, how can they cooperate with each to ensure the two actuators recieve the signal to move?
* How would the order of boards work to ensure success with the project?

## Images

![Electric Blinds_SProposal](https://raw.githubusercontent.com/EGR304-2025-F-105/Team105.github.io/refs/heads/main/docs/image/FINALZT105.png)

**Figure 1:** UML of an electric blinds that activates the motors by the average temperature of both inside/outside of a home and light value. 


## Results

1. Light and Thermo sensor are able to communicate with one another about when the whole system is on and give values of the temperatures to the actuator and IR Emitter.
1. Both the thermoresistor and IR Emitter sensors are working with one another to make sure that the motor does it goal: move in either forward or backwards.


## Conclusions and Future Work

With the proposal, the communication between all four PCBs are visualized to show the internal works of the coding and how it should fuction before the main build. When deciding who goes first, the lgiht sensor was choosen to show how the product turns on/ off to allow the others to function. The thermometer detects the temperature value which then transfers to the IR Emitter which as long as the light value is above 500, it would allow the motor to function until a sudden light change happens to prevent accidents.

## Reflections

After the demonstration, there are several changes the could've happen to improve the quality of the project. First, it would be the layout of the coding as it was confusing when trying to put the whole subsystem all together. Though individuality each subsystem worked, there were issues of trying to tell one another about the high/low values. One solution would be further research about the ADC file given by MPLABX to see which code to properly use instead of guessing. 

## External Links

[Software Proposal Draw.io](https://app.diagrams.net/#G1wC5pWVfzkhPJWQpIBmeiUbisRbVUanYt#%7B%22pageId%22%3A%22WzpfuVUmJpjsxw9uIVLz%22%7D)




