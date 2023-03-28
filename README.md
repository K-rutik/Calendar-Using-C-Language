# Calendar-Using-C-Language
This code is a C program that displays a calendar for any given year and month. The program takes input from the user for the year and month and then displays the calendar using the console. The program also has the ability to navigate to the next or previous month, year or to a particular year and month. The user can exit the program using the "ESC" key.

The program starts by including the necessary libraries for the console, standard input and output, and some required functions. The program then defines the required functions, including "gotoxy", "SetColor", "display", and "calendar".

The "gotoxy" function is used to move the cursor position to the given X and Y coordinates on the console. The "SetColor" function is used to change the text color on the console to the given color code. The "display" function is used to display the days of the month in the calendar grid. Finally, the "calendar" function is used to display the entire calendar for a given month and year.

After defining these functions, the program initializes some arrays to store the names of the months and the days of the week. It then defines the main function, which starts by getting the year and month input from the user. If the year entered is less than 1945, the program prompts the user to enter a year greater than 1945. If the year entered is greater than or equal to 1945, the program calls the "calendar" function to display the calendar for the entered year and month.

After displaying the calendar, the program waits for user input to navigate to the next or previous month, year or to a particular year and month. The program uses the "getkey" function to get input from the user. Depending on the user input, the program calls the "calendar" function to display the next or previous month, year or the selected year and month. If the user presses the "ESC" key, the program exits.
