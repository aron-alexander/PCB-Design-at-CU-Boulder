# PCB-Design-at-CU-Boulder
This repository was made as a way of tracking my progress through the [Practical PCB Design course](https://catalog.colorado.edu/undergraduate/colleges-schools/engineering-applied-science/programs-study/electrical-computer-energy-engineering/#coursestext:~:text=ECEN%C2%A03730%20(3)%20Practical%20Printed%20Circuit%20Board%20Design%20and%20Manufacture) at CU Boulder during the Fall 2024 semester.  The class was originally designed by [Eric Bogatin](https://www.colorado.edu/faculty/bogatin/) and taught by Tim Swettlen.  Over the course of the semester, I designed four PC boards, each with their own unique challenges and learning goals.  [JLCPCB](https://jlcpcb.com/?from=VGSU&gclid=CjwKCAjw8rW2BhAgEiwAoRO5rJBCxvDPFwXZ_TQFcIDn3ufKJMpjLcSdY6q0oR5HRACz8j1c509opxoCp5MQAvD_BwE) was used as the fabrication vendor, so all the boards were designed with their specific limitations in mind.  A brief overview of the four PC boards is given below.

## Board 1: Astable 555 Timer to Drive LEDs
This board is a simple 555 timer circuit operating in astable mode.  The main goal of this board was to become familiar with the full PCB design process from block diagram sketch all the way through to the final assembly and bring-up of the board. 

## Board 2: Good and Bad Hex Inverter Circuits 
This board incorporates two versions of the same circuit: one designed using good practices, and one designed with bad practices.  This allows for clear demonstration of why certain design choices should or should not be made on any PC board, all in one board.

## Board 3: Golden Arduino
This board is a fully functional microcontroller based on the Arduino Uno R3.  The board incorporates design practices that improve performance compared to commercial Arduino boards and clones.

## Board 4: 4-Layer Instrument Droid
This board is a 4-layer shield designed to plug directly into any Arduino Uno R3 board.  Its main function is to characterize a wide range of voltage sources, determining their Thevenin voltages and resistances.  It also incorporates smart LEDs and a buzzer for some fun interactivity.