# Tetris
*****OOP Project Tetris*****
Code Description:
The folder conatins two solutions one that is for visual studio 15 (2017 Version) & the other folder contains visual studio 16 (2019 Version)
The code is built in and for Visual studio 2017 and runs properly. However, it was modified for Visual Studio 2019 & it runs fine for it also.
You can run the code on any version but we recommend you to run it on Visual Studio 2017.

The folder conatins three header files i.e box.h, piece.h, board.h and a main.cpp file

The header file (box.h) contains a class that contains the functions for the color of pieces on the board and a virtual function to print these boxes.
The header file (piece.h) contains functions used for movement of pieces on board. It has box.h inherited
The header file (board.h) contains functions that create the board, generates pieces and other functions that perform several activities of pieces on game board.
It has Piece class inherited and accesses the virtual function print.

The main.cpp contains the board.h called and all the graphics functions.
It contains an object of board class that calls all the required functions.


How to RUN the Code:
The code is built using SFML & TGUI graphics library.
You have to download SFML(2.5.1-2017-32bit) and TGUI(0.8.8-2017-32bit) from their websites
We have built the code on Visual Studio 2017 as SFML was last released for VS 2017.
Open either folder VS17 or VS19.(The one in which you want to run the program). 
After successful setup of SFML & TGUI lib, include, bin, linker; just press run and compiler will build and run the code.
Note:  SFML and TGUI versions will be the same for both VS17 & VS19.

Website links:
https://www.sfml-dev.org/download/sfml/2.5.1/
https://tgui.eu/download/

How to Play the Game:
Press arrow key "UP" to rotate the piece.
Press arrow key "DOWN" to bring the piece downward quickly.
Press arrow key "LEFT" to move the piece in left direction.
Press arrow key "RIGHT" to move the piece in right direction.



 
