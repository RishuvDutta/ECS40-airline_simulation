# ECS40-airline_simulation
C++ program that simulates an airline reservation system.

The program reads  in the information from the file reservations.txt, add passengers to specified flights, and then write a new
file, reservations2.txt that contains all of the updated information.

The reservations text files are a bit complex. The first line indicates how many flights there are. There then is a series of
lines for each flight. For each flight the lines will be: 1) flight number; 2) Origin city; 3) destination city; 4) number of rows, width of rows, and number of seats already reserved; and lines 5 on) row number, seat letter, and name of each passenger. 

The program is made up of 4 different files each with a header file with the exception of main.cpp.
