Create a program to display text paragraphs on an SSD1306 based display with
word-wrapping and auto scrolling
IDE: Arduino or similar
Target board: Arduino Pro Mini or similar (ATMEGA328P, 32kB Flash)
Your task is to:
1. Create a program that takes a string received from SoftwareSerial (the serial device will be a BLE
peripheral device) and display the received text on a 128x64 display based on the SSD1306
driver, with word wrapping (IE no word should be cut off, and should instead wrap to the next
line). If the text/paragraph received from the serial device is longer than what fits on the display,
the display should automatically scroll down (each line should scroll vertically down at an interval
of 500ms) so that all the text is visible on the display.
Note:
a. The input text may be of any length (a few characters, or even a paragraph with 100+
words and several thousand characters).
b. You may use any graphics library of your choice, or even create your own library for the
SSD1306 driver
c. The font size may be any standard 5x7 pixel font
d. Each new string received should start printing from the beginning of the display (0,0
cursor position)
2. You will also submit a document that outlines
(a) your project plan to implement the above - the steps you will take, the timeline you expect
each task to take. Include the date you started the assignment and the date you completed it.
(b) documentation - code should have easy to understand comments, have a readme file for your
additional code explaining what you’ve done, why you’ve done it & any issues/bugs you’ve
resolved and how you resolved them. Please create a private GitHub repository and push your
code as multiple commits.
(c) bug tracking - list out any bugs you’ve observed and try to resolve them
