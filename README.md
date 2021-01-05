# HERO Control System

## Display Pages
- Home Page (Game Controller Not Plugged In)
- Motor Control Page (First Page): Shows the x and y values and the angle of the left joystick in Percent Output mode
- Motion Magic Page (Second Page): Shows the number of ticks and rotations counted in Motion Magic mode
- Motion Magic Saved Values Page (Third Page): Shows the saved number of ticks in Motion Magic mode
- Motion Magic Settings Page (Fourth Page): Shows the max rotation, cruise velocity, and acceleration in Motion Magic mode
- Pneumatic Control Page (Fifth Page): Shows the state of the piston, the system sleep time, and the pulse speed of the piston

## Game Controller

- Left Joystick: Changes the output of the motor in Percent Output mode and the number of ticks in Motion Magic mode 
- Right Joystick: Changes the pulse speed of the piston and the system sleep time
- X, Y, A, and B Buttons: Saves the number of ticks in Motion Magic mode
- Front Top-Left Button: Switches the Control Mode between Percent Output mode and Motion Magic mode
- Front Top-Right Button: Switches the state of the piston from in to out or out to in
- Back Top-Left Button: Goes to the previous page on the display
- Back Top-Right Button: Goes to the next page on the display

## Potentiometer

- Potentiometer 1 (Pin 3): Configures the max number of rotations of the motor for Motion Magic
- Potentiometer 2 (Pin 4): Configures the cruise velocity of the motion for Motion Magic
- Potentiometer 3 (Pin 5): Configures the acceleration of the motion for Motion Magic 

## Saving Values In Motion Magic

1. Make sure that the Control Mode is in Motion Magic mode (press the front top-left button on the game controller if necessary)
2. Move the left joystick around on the y-axis until the motor is at the desired position (can't be 0 ticks)
3. Click on either the X, Y, A, or B button on the game controller while holding onto the left joystick
4. Go to the Motion Values Page and check if the value is saved (use the back buttons to switch between pages)

## Going Back To The Saved Position In Motion Magic

1. Make sure that the Control Mode is in Motion Magic mode (press the front top-left button on the game controller if necessary)
2. Let go of the left joystick so that the number of ticks counted (could be seen on the Motion Magic page) is 0
3. Click on the button (X, Y, A, or B) where the position/value was saved (could be found on the Motion Values page)
4. If the value was saved correctly, the motor should go to that position right away and stay there
5. The matching square (X, Y, A, or B) on the Motion Value page should light green, signalling that the position is locked
6. Press on the same button again to unlock the saved position, and the motor would go back to its default position (0 ticks)
7. Press on a different button with a saved position/value to skip to another position

- Lock Position: Press on a button (X, Y, A, or B) with its matching square on the Motion Values page white 
- Unlock Position: Press on a button (X, Y, A, or B) with its matching square on the Motion Values page green








