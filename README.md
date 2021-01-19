# Debug and Test Stepper Motors

This script uses the *Arduino Serial Monitor* to receive an input to dynamically control different parameters of a stepper motor. This **parameters** are:
- Motor Speed (RPM)
- Motor Steps
- Motor Direction (either 1 (FORWARD) or 2 (BACKWARD))
- Motor Style (either 1 (SINGLE), 2 (DOUBLE), 3 (INTERLEAVE), 4 (MICROSTEP))

Example Input: `<10, 20, 1, 1>` which translates to:
- Set Motor Speed to 10 RPM
- Perform 20 Steps
- Move FORWARD
- in SINGLE steps

NB: This script is based on the excellent post by *Robin2*: https://forum.arduino.cc/index.php?topic=396450.0. The post explains the difficulties when transfering data to the Arduino and how to address them. The script is based on Example 5, and adjusted to work stepper motors.


