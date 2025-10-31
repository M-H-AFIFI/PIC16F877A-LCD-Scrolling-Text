# PIC16F877A-LCD-Scrolling-Text

LCD scrolling text project using PIC16F877A microcontroller.
This project demonstrates how to interface a 16x2 LCD (LM016L) with a PIC16F877A microcontroller in 8-bit mode using mikroC PRO for PIC.
It includes manually written LCD control functions (LCD_Command, LCD_Char, LCD_Print, etc.) — without relying on mikroC’s built-in LCD library.
A smooth scrolling animation is achieved by dynamically shifting a 16-character “window” over a longer message string.

Features:

1-Startup greeting displayed on both LCD lines

2-Smooth text scrolling with wrap-around effect

3-Custom delay for animation speed control

4-Clean pin mapping and commented code for learning

Author: M.H. Afifi

Compiler: mikroC PRO for PIC

MCU: PIC16F877A
