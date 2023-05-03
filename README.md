# Somewhat-Scientific-Calculator
Scientific Calculator using an ARM Cortex M microcontroller

Objective: The objective of this project is to develop a calculator application using an ARM Cortex M microcontroller, which can interface with different peripherals such as keypad and display and perform basic arithmetic operations.



Description: In this project, an ARM Cortex M microcontroller is used to build a calculator application that can perform basic arithmetic operations such as addition, subtraction, multiplication, and division. The microcontroller is interfaced with a keypad and a display, allowing the user to input the numbers and view the result.
The calculator application is designed to be user-friendly and easy to use, with a simple and intuitive interface. The keypad is used to input the numbers, while the display shows the input numbers and the result of the calculation. The microcontroller is programmed to perform the arithmetic operations using software algorithms, which are optimized for speed and accuracy.
The calculator application can be used for a wide range of applications, including educational, scientific, and industrial purposes. It can be easily customized and modified to meet the specific requirements of different applications. The use of an ARM Cortex M microcontroller ensures high performance, low power consumption, and reliable operation, making it an ideal choice for calculator applications.


How to run the program

1.Open Keil µVision4 and create a new project: Click on Project → New µVision Project. Select the directory where you want to save your project and give it a name.

2.Configure the project: Click on Project → Options for Target. Select the Device tab and choose the device that you are using (in this case, NXP LPC1768). Configure other settings in the Configuration WIzard of system_LPC17xx.h

3.Add the source files to the project: Right-click on the Source Group folder in the Project window and select Add Existing Files to Group. Browse to the directory where your source code is saved and select the main.c file. Click Add.

4.Build the project: Click on Project → Build Target. If there are no errors in the code, the project will build successfully and you will see a message saying "Build target 'Target 1' completed."

5.Configure FlashMagic: Open FlashMagic and select the correct serial port and baud rate for your microcontroller board. In the Options menu, make sure that the correct device (NXP LPC1768) is selected.

6.Connect the board to the computer: Connect your microcontroller board to the computer using a USB cable.

7.Load the program: In FlashMagic, select the HEX file that was generated by Keil µVision4. Click on the Start button to begin downloading the program to the board.

![KeilWindow](https://user-images.githubusercontent.com/55918941/235949179-088c6686-c390-41d4-9d32-6745f9a30f7d.png)



Note: Required files to be included like lpc17xx.h, system_LPC17xx.c and startup_LPC17xx.s have been included in the repository for easy access.
