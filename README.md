# Intro-to-CS-II-Final-Project
GUI that overviews basic searching and sorting algorithms

This project is part of my coursework at the University of Nebraska at Omaha. It was coded completely in Python. The project is a GUI that displays an overview and details (runtimes, pros, cons) about the searching and sorting algorithms we learned in class. Then, a user is able to enter in an array of numbers. For a search algorithm, a tracing table is displayed. For a sort algorithm, each step of the sorting process is displayed. 

The main.py file simply runs the GUI. 

The gui.py file contains the class gui, which contains all of the code logic for the gui. This includes displaying all information, storing variables, handling input, and calling functions from the modules.py file. 

The modules.py file contains the modules for the five searching and sorting algorithms. These functions take in an array (and a target if it is a search algorithm) and outputs each step as a formatted string into a list. This list is then returned to the gui class for display on the interface. 

Additional commentary can be found inside the code files in this repository.
