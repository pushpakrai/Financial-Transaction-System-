
# Financial Transaction System

## Overview
A C++ console-based **Personal Finance Management System** to track finances, manage income, expenses, and investments like **SIP** and **FD**, and calculate maturity amounts.

## Features
- **User Account**: Create account with initial balance.
- **Track Transactions**: Record income, expenses, and investments.
- **Investments**: SIP and FD with maturity calculations.
- **Transaction History**: View detailed records.
- **Balance Info**: Check current balance and financial status.

## Class Diagram
![Class Diagram](https://github.com/pushpakrai/Financial-Transaction-System-/blob/main/Financedrawio.png)

## Getting Started

1. **Clone the Repo**:
   ```bash
   git clone <repo-url>
   ```

2. **Compile**:
   ```bash
   g++ main.cpp -o main
   ```

3. **Run**:
   ```bash
   ./main
   ```

## Input/Output Example

```shell
--- Welcome to Finance Management System! ---

1. Record INCOME
2. Record EXPENDITURE
3. Make Investment
4. Finance Info
5. Investment Info
0. Exit
Enter choice : 1
Amount : 5000, Description : Salary

Enter choice : 2
Amount: 2000, Description: Rent

Enter choice : 3
SIP (1) or FD (2): 1
Amount: 500, Duration: 5 yrs, Monthly: 100

Enter choice : 4
Balance: 3700
Income: 5000 (Salary)
Expenditure: 2000 (Rent)

Enter choice : 5
Investment 1: 6806.5 Rs (SIP)
Investment 2: 1207.33 Rs (FD)

Enter choice : 0
```

## Disclaimer
This system is for educational purposes only and doesn't offer real financial advice. Interest rates used are fictional.

## License
Open-source under the [MIT License](LICENSE).

## Acknowledgments
- Educational project developed with help from the C++ community.
