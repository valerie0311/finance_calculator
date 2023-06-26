# finance_calculator
Finance Calculator
This is a simple finance calculator script that allows you to calculate either the amount of interest you will earn on an investment or the amount you will have to pay on a home loan (bond).

Usage
Run the finance_calculator() function.
Choose the program you want to run by typing either "bond" or "investment" when prompted.
Follow the instructions and provide the required inputs.
The calculator will compute the results and display them.

Functions
finance_calculator()
This is the main function that runs the finance calculator. It prompts the user to choose between calculating a bond or an investment. Based on the user's choice, it collects the necessary inputs and performs the calculations.


Input Parameters
amount_invested: The initial amount invested.
interest_rate: The interest rate (expressed as a percentage).
years: The number of years the investment is held for.
interest_type: The type of interest calculation ("simple" or "compound").
Output
The calculated future amount of the investment is displayed.

Error Handling
If the user enters an invalid number, the script will prompt them to enter a valid number.
If the user enters an invalid interest type, they will be prompted to enter either "simple" or "compound".
