# Buzzer to hand sanitizer

This project was my final project for the "Sensors and Electronics" class of my Master's Degree in Biomedical Engineering.

![Front view of the prototype](https://user-images.githubusercontent.com/83720730/156149670-acbddd6d-1ab1-41a0-b1a7-4cc14b1b939e.jpeg)

## The problem it solves

This projects came to mind to solve an existing problem: the problem of people walking by sanitizers without using it.

## Hardware and functionality
- Arduino Uno
- 2 PIR sensors (infrared sensors)
- 1 module groove speaker
- 1 Breadboard
- Some wires

The prototype has two PIR sensors, one on top of the sanitizer, and another half meter ahead of the first. When the first one detects movement, meaning a person disinfected his hands, when he passes the second PIR sensor, the buzzer doesn't give any output sound. But when the second PIR sensor detects movement, without the first one detected, meaning a person passed by the first sensor without disinfecting his hands, the buzzer emits sound.

![Inside view of the prototype](https://user-images.githubusercontent.com/83720730/156150474-a1fa0019-8290-47c7-beb0-6d145d3ad38a.jpeg)
*Inside view of the prototype.*

![PIR sensor on the disinfectant](https://user-images.githubusercontent.com/83720730/156151251-af37ff88-7f41-4221-8e85-f4aa74e421b7.jpeg)
*PIR sensor on the sanitizer.*

## Simulation
This video contains two phases:
The first one is when someone doesn't disinfect their hands, meaning no movement was detected on the left PIR sensor and passes by the second PIR sensor generating a beep. The second is when someone disinfects their hands and consequently passes by the second PIR sensor generating no beep.

https://user-images.githubusercontent.com/83720730/156224831-54ea9cf1-4fa6-47c3-af67-414f92269bb2.mp4

