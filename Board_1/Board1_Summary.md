# Board 1 Overview
Board 1 acted as an introduction to some of the most basic elements and best practices of PCB design in Altium, and provided a brief overview of the full PCB design process. This was done by designing a 555 timer to operate in astable mode. 

The circuit design itself was based on a brief lab completed earlier in the course in which we were asked to design for a frequency of about 500Hz and a duty cycle of about 50%. These exact values were given as rough guidelines, as precise operation of the timer was not the main goal of this project.  The acceptable ranges for this project were a frequency between 300Hz and 1kHz, and a duty cycle between 40% and 75%.

The circuit was powered by a 5V barrel jack, and the 555 timer's output was connected to a group of four red LEDs to give it a bit more visible functionality. Each of the LEDs were connected in series with a different resistance (50Ω, 300Ω, 1kΩ, or 10kΩ) as a demonstration of what resistor/LED combination would make for a good indicator light.

# Circuit Plan and Theory
$$f = \frac{1.44}{(R_A + 2R_B)C} = \frac{1.44}{(1kΩ + 2(1kΩ))(1µF)} = 480Hz$$
$$Duty Cycle = f*0.693(R_A + R_B)C = (480Hz)*0.693((1kΩ)+(1kΩ))(1µF) = 66.5\%$$

# Altium Files
## Circuit Schematic

## PCB Layout

# Physical Board
## Test Points

## Measurements

# Conclusions
