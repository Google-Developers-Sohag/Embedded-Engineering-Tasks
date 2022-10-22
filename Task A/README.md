# Embedded-Engineering-Tasks

## Task A [A proof of concept]:

- Content: A library that controls the GPIO using a Microcontroller (AVR-Preferrable).

- Structure to follow: 
  1) Create a header file `digital.h` and a source file `digital.c`.
  2) `digital.h` has the following: 
      - uint8_t* digitalRead(uint8_t*).
      - void digitalWrite(volatile uint8_t* port, const uint8_t* pin, int).
  3) Create a `main.c` and add an implementation example (blink an LED, Ultrasonic implementation, Traffic Light design,...etc...choose your own).
  4) [Optional] Add an implementation for the external interrupt service subroutine of the available GPIOs.

- UML diagram: 

![](https://github.com/Google-Developers-Sohag/Embedded-Engineering-Tasks/blob/task-a/Task%20A/resources/uml/Digital.svg)

- Learning outcomes: 
  1) Basic AVR programming (avrio).
  2) Basic C application structuring (macros, headers, functions and sources).
  3) Basic native library training.
  4) Building AVR native programs using GCC.
 
- C programming langauge learning outcomes: 
  1) Preprocessor directives (Macros and Conditions).
  2) Boolean algebra.
  3) Type qualifiers (const and volatile -- cv-qualifiers).
  4) Passing parameters by variables V.S. by references (Shallow/Superficial copy V.S. Deep copy).
  5) Returning by values V.S. returning by references.
  6) Different ways of looping in C (loops, recursion, interrupt services using 'goto').
  7) Header and Source files.

- References: 
  1) [IBM C/C++ Language Reference](https://www.ibm.com/docs/en/ssw_ibm_i_74/pdf/sc097852.pdf).
  2) [AVR-libs structure documentation](https://www.nongnu.org/avr-libc/user-manual/library.html).
  3) [GNU GCC](https://gcc.gnu.org/onlinedocs/gcc.pdf).

-----------------------------------------------------------------------------------------------------
