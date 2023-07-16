# Programmable-Led-Matrix

The following C++ code is intended to control an 8x8 LED matrix display. It specifies the row and column pins used to operate the LEDs. It also provides arrays that depict various patterns such as integers (3, 2, 1), shapes (heart, smiling), and characters.

The setup() method starts the serial transmission and assigns the pins provided as OUTPUT. It sets the pins' original state to LOW.

The primary element of the code that runs continually is the loop() method. It makes many calls to the led() method with varying patterns and delays between each one.

The led() method accepts a 2D array containing the LED pattern to display. It iterates across the columns and rows of the LED matrix, setting the relevant pins depending on the pattern array values. The pins are controlled by digitalWrite.

Overall, the code initialises the LED matrix and loops through various patterns on it. Before transitioning to the next pattern, each pattern is presented for 500 milliseconds. Change the values in the pattern arrays to customise the patterns.

![image](https://github.com/Tarunlol/Programmable-Led-Matrix/assets/117750351/bfcd65e2-88e8-4d6b-b0c3-c015c027f5d5)

