# Seat-Discount-System
First year "Introduction to Programming" module coursework
Coursework 1:
A new seat discount system is required to help managers of a railway company determine how much discount they 
have given out. Every time the system runs, the discount rate may be specified by the managers or set to a suitable 
default. You are thusly required to produce a console application (using Java) that is ready to open the file seats.txt 
which contains the seat’s data. 
 
NOTE : The seats.txt file (i.e. Appendix A) is provided on Canvas in the Assignments section. 
You should download the file and add it to your Java project. 
It contains four sample seats. The format of each seat’s data is as follows : 
 
seat type 
seat price 
number of bookings 
 
Upon application launches, the system should ask the managers if they wish to specify a custom discount rate, this 
should be in the form of a yes / no (Y/N) question. When the managers say yes, the system should request the 
discount rate as input (from the keyboard) which will then overwrite the default discount rate (i.e. Appendix B). 
When the managers say no, the system should report (to the screen) the default discount rate (i.e. Appendix C). 
Next, the system should loop through the seat’s data, calculating and printing (to the screen) the seat type, seat 
price, number of bookings, discount and income following discount, the latter two requiring some basic 
calculations. 
 
Finally, the running totals for the discount and income following discount should be calculated and printed before 
the application gracefully exits.
