
# Canteen Billing System

## Project Description

The Canteen Billing System is a simple Python project developed to manage customers, food orders, billing, and payments in a college canteen.

The project is divided into different Python modules. Each module performs a specific task such as displaying the main menu, managing food items, taking orders, generating bills, processing payments, and printing the final receipt.

## Features

- Add customer details
- Generate customer ID
- Display food menu
- Take food orders
- Enter quantity
- Calculate item-wise amount
- Calculate subtotal
- Calculate 5% tax
- Calculate grand total
- Payment through Cash, UPI, or Card
- Print final receipt
- Display date and time
- Handle invalid inputs
- Return to the main menu
- Exit the system

## Technologies Used

- Python 3
- Jupyter Notebook
- Google Colab
- Python Modules

## Project Files

1. main.py - Controls the complete program.
2. main_menu.py - Displays the main menu.
3. food_menu.py - Stores and displays food items and prices.
4. take_order.py - Takes customer orders and quantities.
5. generate_bill.py - Calculates subtotal, tax, and grand total.
6. payment.py - Processes payment and prints the receipt.
7. user_customer.py - Handles customer details and connects all modules.

## Food Menu

- Tea - Rs. 15
- Coffee - Rs. 25
- Samosa - Rs. 20
- Sandwich - Rs. 60
- Burger - Rs. 100
- Pizza - Rs. 150
- Pasta - Rs. 120
- Cold Drink - Rs. 40

## Program Flow

Main Menu
    |
    v
Add Customer
    |
    v
Customer Details
    |
    v
Food Menu
    |
    v
Take Order
    |
    v
Generate Bill
    |
    v
Payment
    |
    v
Print Receipt
    |
    v
Return to Main Menu

## Input Validation

The program checks:

- Phone number must contain exactly 10 digits.
- Food item number must be valid.
- Quantity must be greater than zero.
- Invalid payment methods are rejected.
- Invalid numeric input is handled using try-except.

## How to Run

### Jupyter Notebook

Run all the module cells first and then run:

%run main.py

### Google Colab

Run all the module cells first and then run:

!python main.py

## Python Concepts Used

- Functions
- Modules
- Lists
- Dictionaries
- Loops
- Conditional statements
- Exception handling
- String methods
- Global variables
- Import statements
- Date and time

## Future Improvements

- Save bills to a file
- Add customer search
- Add/remove items from an order
- Add sales reports
- Add database support
- Add a graphical user interface

## Conclusion

The Canteen Billing System is a beginner-friendly Python project that demonstrates how different modules can work together to manage customers, orders, billing, and payments.

## Author

Name: Kriti Rasela

Project: Canteen Billing System
