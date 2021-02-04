# picopomodoro
A Pomodoro timer using Raspberry Pi Pico.

The Pomodoro Technique was developed by Francesco Cirillo using a tomato-shaped kitchen timer (hence the name). It breaks down longer periods of work into 25 minute sessions, with a five minute rest between each one. Several smartphone apps replicate the timer experience.

This uses a Raspberry Pi Pico and Unicorn Pack instead. Press the X button to start a work session and the LEDs illuminate in red, then blink out one at a time over the course of 25 minutes. After the work cycle completes, the LEDs illuminate green and blink out over five minutes. The process then repeats by initiating a new work cycle.

The alternating cycles continue until the Y button is pressed. This terminates the process and returns the Pico to its rest state.
