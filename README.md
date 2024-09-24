# Collatz

Generates the hailstone sequence for up to twenty integers using parallel programming and returns the total stopping time and upper bound for each.

___
## About The Project
The Collatz Conjecture is an unsolved problem in Number Theory. It is famous as the problem statement can be understood by anyone with only a background in elementary school arithmetic, yet remains unsolved to this day despite being introduced in 1937.

To generate the hailstone sequence for any positive integer, multiply the number by 3 and add 1 if the integer is odd and divide by 2 if the integer is even. Repeat this process until 1 is obtained. For example, the hailstone sequence for 9 is {9, 28, 14, 7, 22, 11, 34, 17, 52, 26, 13, 40, 20, 10, 5, 16, 8, 4, 2, 1}. The Collatz Conjecture states that the hailstone sequence for every positive integer will eventually reach 1. The number of steps needed to reach 1 is called the total stopping time and the largest number occurring in the sequence is called the upper bound. The total stopping time for the sequence given earlier is 19, and the upper bound is 52.

This project allows the user to input up to twenty integers between 1 and 999,999,999,999,999,999 and returns the total stopping time and upper bound for each.

___
## Installation
This project runs in Jupyter Notebook. To use Jupyter Notebook it is necessary to download and install [Anaconda](https://www.anaconda.com/download). Once installed, Jupyter Notebook can be accessed through the Anaconda Navigator.

To run the code, the following packages must be installed:
- tkinter
- multiprocess

These packages can be installed by opening a new terminal in Jupyter Notebook and using the following command:

```pip install [Insert package name here.]```

Where the brackets should be replaced with the package name. For example, to install multiprocess enter the command:

```pip install multiprocess```

___
## Instructions
To begin input up to twenty integers, separated by commas, between 1 and 999999999999999999. Click submit and the total stopping time and upper bound will be printed in the app. The program uses multiprocessing, so the runtime only depends on the maximum total stopping time, not on the number of integers entered.

Note: To view this information in the app, click the "Help" button in the lower left.

___
## Acknowledgements
I would like to thank the creators of the multiprocess package. It was valuable in reducing the programs' runtime.

I thank the owner of the YouTube channel Clear Code. His tkinter tutorial helped me learn how to create user interfaces in Python. Including the one for this project.

Note: To view this information in the app, click the "Acknowledgements" button in the lower right.

___
## Disclaimer
This project was originally created by Joseph W Barnett. If credit is given to the original author, it can be altered and distributed for noncommercial use.
