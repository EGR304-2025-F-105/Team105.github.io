---
title: Team Block Diagram
---

## Introduction

The group decided that the electric blinds would require the the 4 main functionalities: light sensor, thermoresistor, IR emitter detector pair and an actuator.

## Research Question

* How can we ensure that the connectors are correctly place?
* How can we tell the product to stop when there is something blocking (going more into depth about the scenerio coding)?
* How can we work the light sensor and the thermoresistor sensors together to tell the product the light and temperature value?

## Team Block Diagram

![Team Block Diagram](https://raw.githubusercontent.com/EGR304-2025-F-105/Team105.github.io/refs/heads/main/docs/image/2FIN_Team105.png)


## Conclusions

With the diagram, it showcases the links that each funcation has and how it connects to one another through the wiring. There are three major parts to the subsystem which are the following: having the light sensor turning on everything, the thermoresistor getting temperature values, and the motors working together to showcase the movement of blinds. Going back to the wiring, the whole board is connect through pins one and two on the connectors dependent on the PCB boards. Furthermore, the connectors pins are than inputted into either the PIC's RC4 or RC5 to make it easier to read for the group. To ensure the connection is being read through everyone's subsystems, the team matched the input and output to one another, so the data is transfered smoothly.

There were a number of changes which are listed down below.
1. What the values mean: the team decided that instead of having both Keith's and Abriana's work separately, Keith's tells Abriana's that it should be working through a high/low value. This would then have Abriana's have the High value until it reaches a certain light value. This data is then given to Tim's subsystem.
1. Unfortunate, Abriana's subsystem was not working during the time of demonstration, so the team had to connect Keith's and Tim's subsystem so that Tim recieves data. With that, the motor would run when down if the height reaches a certain temperature. 
1. For the start of the system, the team decided to show the motor to go forward first for the first couple seconds before switching to the opposite direction to show the code working.
1. Originally, there were two motors; however, they worked too similarly, so the team decided to do three sensors and one actuator. 
1. Another change from the original was that the light and thermoresistor sensors had used the same op-amp system layout, but now one uses the inverse of the op-amp.



## External Links

[draw.io](https://app.diagrams.net/#G1Bh6cie3VpDT83jYh41SfBJG12mz2PesZ#%7B%22pageId%22%3A%229SEZQWnZX4QmiDfSKDef%22%7D)

