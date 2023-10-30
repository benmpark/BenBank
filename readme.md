# Bank of Ben

## Overview
This repository contains a basic banking application with various (simulated) functions (i.e., you cannot use this program to actually add money to your real bank account!). The main menu, which lists the actions that the user can perform, is detailed below. This application was created as part of a final project for a Foundations of Program class at Merrimack College (CSC6003).

## Installation and Running the Programs
Once you have [Python](https://www.python.org/downloads/) installed on your machine, you are almost good to go. The entry point for running the program is the **parkfinal.py** file; all the other Python files must be in the same directory, of course (this includes **BenAccount.py**, **BenATMachine.py**, **BenBank.py**, **BenBankManager.py**, **BenBankUtility.py**, and **BenCoinCollector.py**. Running the **BenBank.py** file is sufficient, as functions are drawn from the other files with the necessary import statements.

Once in the proper directory, the program can be run via the following command:
`python3 parkfinal.py`

### Navigating the Program
The program will bring you to the main menu, where you'll have a series of actions to choose from:
1. Open Account
2. Get Account Information and Balance
3. Change PIN
4. Make a Deposit
5. Transfer Funds
6. Withdraw Money
7. ATM Withdrawal
8. Deposit Change
9. Close an Account
10. Add Monthly Interest to All Acounts
11. End Program
At the beginning you will have to open an account, as all other options (other than quitting) won't make sense if there are no open accounts. As you are opening your account, note your account number and PIN, as you will need to enter those each time you wish to perform an action relating to your account. (And there need to be at least two accounts open if you want to attempt transferring funds between accounts.)

## Documentation
A series of HTML files (one for each of the aforementioned .py files) contains the documentation for the program. Python docstrings can also be generated from the source code itself.

## License
MIT License

Copyright (c) 2023 Benjamin Park

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
