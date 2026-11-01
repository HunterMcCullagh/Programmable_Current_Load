# Programmable_Current_Load
The purpose of this project is to create an electronics evaluation tool to see how circuits function when a current drain is applied. Some possible test scenarios include speeding up the process of a battery drain to see how circuits function with an almost depleted battery, and applying current changes to a power supply to see any changes in the voltage.

The circuit functions through an analog control loop using MOSFETs to control the amount of current going through a 100mΩ resistor. Large copper pads are also included in the design to allow large heatsinks to be attached when using this circuit board with alrge currents.

An STM32 is used to control the current through a PWM signal which is interfaceable with a PC over the USB-C port. Additional GPIO are also broken out to allow for an OLED display, switches, or dials which will be added when I design a mechanical enclosure for the system.

<img width="877" height="855" alt="3D_Picture" src="https://github.com/user-attachments/assets/87005801-ae4d-4305-939c-bdc84eb6d394" />
