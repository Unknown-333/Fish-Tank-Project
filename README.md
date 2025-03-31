Project Overview

This is a simple graphical animation created using the Borland Graphics Interface (BGI) library in C. The animation depicts a fish tank with two swimming fish, an oxygen tank with bubbling oxygen, and decorative stones at the bottom.
Features

    Animated Fish:

        Two fish swimming in opposite directions (left to right and right to left)

        Each fish has basic body shapes and eyes

    Oxygen System:

        Oxygen tank with bubbling animation

        Bubbles rising from the tank to the surface

    Fish Tank Environment:

        Glass tank with 3D perspective (angled sides)

        Decorative stones at the bottom

        Water surface at the top

Technical Details
Libraries Used

    graphics.h - For graphical operations

    conio.h - For console input/output

    stdio.h - Standard I/O

    dos.h - For delay function

Functions

    oxygen_bubbles(int i, int y):

        Handles the animation of oxygen bubbles rising

        Takes current animation frame i and y-position y as parameters

        Manages two alternating bubbles for continuous animation

    main():

        Initializes graphics mode

        Contains the main animation loop

        Draws all elements (fish, tank, bubbles, stones)

        Uses cleardevice() and delay() for animation effect

Compilation Notes

    Requires Borland Turbo C++ or compatible compiler

    BGI path must be correctly specified in initgraph()

    Original path is set to "C:\TC\BGI" - modify as needed for your system

How to Run

    Ensure you have a Turbo C++ environment set up

    Compile and run the program

    The animation will play automatically

    Press any key to exit

GitHub Repository Structure
Copy

fish-tank-animation/
│
├── src/
│   └── fish_tank.c       # Main source code
│
├── docs/
│   └── README.md         # This documentation
│
└── assets/               # (Optional)
    ├── screenshot.png    # Sample output
    └── demo.gif          # Animated demo

Customization Options

    Modify fish shapes by changing the line/circle coordinates

    Adjust animation speed by changing the delay() value

    Add more fish or decorative elements

    Change bubble patterns by modifying the oxygen_bubbles() function

Limitations

    Requires legacy BGI graphics library

    Fixed resolution (uses default graphics mode)

    Simple animation without user interaction

This project serves as a good example of basic computer graphics animation principles using the BGI library. It demonstrates frame-by-frame animation, shape drawing, and simple motion algorithms.
