# Task-2---Implementation

This is a console-based Java application that lets users choose, view, and store car data interactively. The program provides a straightforward yet useful menu-driven interface via which users can carry out a number of vehicle management-related tasks.

Vehicle Class:
IT represents a car using characteristics such the model, year, manufacturer, and type. It offers a toString function for easy string representation and a constructor to initialize vehicle data.

VehicleStorage Class:
It acts as a storage space for particular cars. It manages a list of Vehicle objects dynamically by using an ArrayList.

FileHandler Class:
It controls how some cars are exported to a CSV file. It implements the exportToCSV function, which uses a given file name to send vehicle information to a file.

TerminalMenu Class:
The TerminalMenu Class uses a terminal-based menu system to control the user interface. It enables users to choose which automobiles to see, save which vehicles to a file, and quit the application. It implements utility methods for handling user input and retrieving the current date and time, as well as methods for each menu choice.

VehicleSelectionApp Class:
The VehicleSelectionApp Class includes the main function that starts the application's execution in an infinite loop until the user decides to stop it. This method initializes the TerminalMenu.
