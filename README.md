# Discount Calculator

## Overview
This project contains a Python program that calculates the final price of an item after applying a discount. It helps users quickly determine the discounted price based on the original price and discount percentage.

## Features
- Calculates discounted price if discount is 20% or higher
- Returns original price if discount is less than 20%
- Simple and easy-to-use user input interface
- Works for any positive numeric price and discount

## How It Works
The program uses a function called `calculate_discount(price, discount_percent)` that:
1. Accepts the original price and discount percentage as parameters
2. Checks if the discount percentage is 20% or higher
3. If yes, applies the discount and returns the final price
4. If not, returns the original price

The program then prompts the user to:
- Enter the original price of the item
- Enter the discount percentage

Finally, it prints the final price after applying the discount or the original price if no discount is applied.

## Example1
Enter the original price: 100
Enter the discount percentage: 25
Final price after discount: 75.0

## Example2
Enter the original price: 100
Enter the discount percentage: 10
No discount applied. Original price: 100


## Usage
1. Clone or download this repository
2. Run the Python file:
```bash
python discount_calculator.py

## Author
**Dereje Masresha**  
GitHub: [Deremas](https://github.com/Deremas)
