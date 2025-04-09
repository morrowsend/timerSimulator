# Microcontroller PWM Timer Simulator

This repo have a few examples showing how the timer in a microcontroller works graphically.

The file names "1 set CMP Value Vertical.p5js" is the most up-to-date code with all the features. It is the best file to use to see how 8-bit timers work. Paste its code into [https://editor.p5js.org/](https://editor.p5js.org/)

==========

Once running in the P5.js editor, click on the app pane and control values with keypresses. the outputs of these are shown on the console

Key commands are as follows:
- W or w = Increases the maximum waveform Frequency
- S or s = Decreases the maximum waveform Frequency
- O or o = Descrease prescaler (only values 1, 2, 4)
- P or p = Increase prescaler (only values 1, 2, 4)
- N or n = Decrease compare value (or duty cycle)
- M or m = increase Compare value (or duty cycle)
- i or I inverts the value of the PWM. (whether it is right or left-aligned)
