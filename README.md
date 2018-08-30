# BBB-RoboBoard
Code from my Thesis project: a BeagleBone Black robotics platform.

This code was developed with the help of Dr. George Engel of University of Illinois Edwardsville

Designed to run on the original BeagleBone Black, this project takes advantage of the two PRU (programmable real-time unit)
processors that sit next to the main ARM core in the ARM Cortex-A8 chip and turn them into motorcontrollers. The intent is 
to allow robotics teams to get moving with minimal effort. PRU0 controls PWM signals for each motor's driver while PRU1 handles
a PID controller using wheel encoder ticks as feedback. A GUI is also supplied to help make the fine tuning of PID parameters easier.

With this build only two motor drivers work (M1, M2) with the PID loop. More development work will hopefully be done in the future

More information can be found in the thesis document "cfaber_thesis.pdf"
