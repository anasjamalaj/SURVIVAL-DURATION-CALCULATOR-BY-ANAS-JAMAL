# Survival Duration Calculator

## Project Description

The Survival Duration Calculator is a Python program that calculates the duration of how long a person has lived based on their age. The program allows the user to input their age and choose a time unit (Months, Weeks, Days, Hours, Minutes, Seconds), and then calculates and displays the duration they have lived in that time unit.

## Project Implementation

The program uses a function called `duration_of_survival()` to handle the calculation of the survival duration. It prompts the user to enter their age and choose a time unit. The program also allows the user to use shortcuts for time units (e.g., 'm' for months, 'mi' for minutes) to make it more user-friendly.

The program then calculates the duration of how long the person has lived based on their age. For example, it calculates the number of months by multiplying the age by 12, the number of weeks by multiplying the number of months by 4, and so on for days, hours, minutes, and seconds.

Based on the user's choice of time unit, the program displays the calculated duration in that unit. If the user enters an invalid time unit, the program displays a message indicating that the choice is not available.

## Usage

To use the program, run the `duration_of_survival()` function. Enter your age when prompted and choose a time unit. The program will then calculate and display the duration you have lived in that time unit.
