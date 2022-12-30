# Understanding Embedded Systems

### __Table of Contents__: 

- Understanding Embedded Architecture
- Creating a Systems Architecture 
- Code Examples
- Outputs/ Inputs/ Timers
- Task Management
- Communicating with Peripherals
- Updating Code
- Math
- Reducing Power Consumption 




### __Understanding Embedded Architecture__

_**Microcontroller**_ - Essentially a collection of a processor (CPU), some memory (volatile/non-volatile/hybrid), and an I/O peripheral. 
Within an embedded system, microcontrollers govern one specific part of the overall logic of that particular system. 

_**Embedded System**_ - A group of different hardware and software specifications in order to complete a specific task. 
 A good example would be a robot controlled arm within a kitchen that is capable of moving and assembling different ingredients and preparing them. 
Microcontrollers would be placed at each 'joint' of the robot arm, which would give it a specific function which corresponds to 3-D movement.

_**RAM**_ :

- _**SRAM**_ - 'Static RAM' Used for faster computations than a DRAM. SRAM is usually coupled with processors or close to the 1st level cache since it is
faster. Memory-wise, SRAM is not able to store a lot, so that is a drawback along with the fact that it is volatile (memory erased upon system shutdown).

- _**DRAM**_ - 'Dynamic RAM' More memory-space than a SRAM, however, in terms of speed, it is lacking. DRAM has a simple structure, so working with it is 
relatively easier. It also has a similar drawback in that once the power is cut off, the memory is erased. Also, DRAM is much costlier in terms of 
energy usage than the SRAM since it relies on the strength of capacitors instead of transistors. 

- _**NVRAM**_ - 'Non-volatile RAM' Combination of both an SRAM and a EEPROM (Electronically-Erasible Programmable Read-Only Memory). 
The speed of an SRAM is used for operations and storing certain information, while the state of the SRAM is stored within the 
EEPROM using either a value of 0 or 1 representing either same-state or a state-shift. 

