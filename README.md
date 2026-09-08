Worker Contract Management System

A Java program that simulates registering a worker and their hourly contracts. The system reads a worker's data (name, level, and base salary) along with N associated contracts
(date, hourly rate, and duration), allowing the calculation of the employee's total income for a specific month provided by the user.

Features:

Worker registration with level (JUNIOR, MID_LEVEL, SENIOR)
Association of multiple hourly contracts (HourContract)
Worker linked to a department (Department)
Monthly income calculation based on contracts for the given month/year

Technologies: Java, Object-Oriented Programming (OOP)

Example:

Enter department's name: **Design**
Enter worker data:
Name: **Alex**
Level: **MID_LEVEL**
Base salary: **1200.00**
How many contracts to this worker? **3**
Enter contract #1 data:
Date (DD/MM/YYYY): **20/08/2018**
Value per hour: **50.00**
Duration (hours): **20**
Enter contract #2 data:
Date (DD/MM/YYYY): **13/06/2018**
Value per hour: **30.00**
Duration (hours): **18**
Enter contract #3 data:
Date (DD/MM/YYYY): **25/08/2018**
Value per hour: **80.00**
Duration (hours): **10**

Enter month and year to calculate income (MM/YYYY): **08/2018**
Name: Alex
Department: Design
Income for 08/2018: 3000.00
