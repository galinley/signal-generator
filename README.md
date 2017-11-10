# signal-generator
Generate a sudo-random signal to use for RNN training

This Python application will attempt to initialize using a GUI to allow users to specify certain signal generation parameters.  If the required Tkinter package is not available to import, then the application will continue using inputs from the command line.

This application will generate points given a base function to simulate a semi-random signal.
Example:
If the base function used to generate the signal is: f(x) = sin(x)
Then each value of f(x) will be offset by a value of c, which will be a random number between [-b, b] where b defaults to 0.1, but can be adjusted by the user. So the final values for f(x) will be:
f(x) = sin(x) + c 
where c is in [-b, b].


User adjustable parameters:
- Input function: Selectable from a predefined list
- Spread: 
