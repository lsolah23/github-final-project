A calculator that calculates simple interest given principal, annual rate of interest and time period in years.

Input:
   p, principal amount
   t, time period in years
   r, annual rate of interest
Output
   simple interest = p*t*r

--------------------------------------------------------

Simple Interest Calculator

A lightweight calculator that computes simple interest given principal amount, annual rate of interest, and time period in years.

Description
This project provides a straightforward implementation for calculating simple interest using the standard formula. Simple interest is calculated as a percentage of the principal amount for the entire loan period, making it an essential financial calculation tool for loans, investments, and other financial planning scenarios.

Formula
Simple Interest = P × T × R
Where:

P = Principal amount (initial sum of money)
T = Time period in years
R = Annual rate of interest (as a decimal)

Input Parameters

p - Principal amount (numeric value)
t - Time period in years (numeric value)
r - Annual rate of interest (as a decimal, e.g., 0.05 for 5%)

Output

simple interest - The calculated simple interest amount

Getting Started
Prerequisites
 
Installation
Clone the repository:
bashgit clone https://github.com/yourusername/simple-interest-calculator.git

Navigate to the project directory:
bashcd simple-interest-calculator

Usage
Basic Example
Input:
  p = 1000 (principal amount)
  t = 2 (time in years)
  r = 0.05 (5% annual interest rate)

Output:
  simple interest = 1000 × 2 × 0.05 = 100
Code Example
python# Example implementation (adjust based on your programming language)
def calculate_simple_interest(p, t, r):
    """
    Calculate simple interest
    
    Args:
        p (float): Principal amount
        t (float): Time period in years
        r (float): Annual rate of interest (as decimal)
    
    Returns:
        float: Simple interest amount
    """
    return p * t * r

# Usage
principal = 1000
time_years = 2
interest_rate = 0.05

interest = calculate_simple_interest(principal, time_years, interest_rate)
print(f"Simple Interest: ${interest}")
Features

✅ Simple and intuitive calculation
✅ Handles various input ranges
✅ Lightweight implementation
✅ Clear input/output format


Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

Guidelines

Ensure your code follows the project's coding standards
Add tests for new features
Update documentation as needed
Make sure all tests pass before submitting

Roadmap

 Add support for compound interest calculation
 Implement input validation
 Add GUI interface
 Create web-based calculator
 Add currency formatting options

License
This project is licensed under the Apache 2.0 License - see the LICENSE file for details.
Support

If you encounter any issues or have questions, please:

Check the Issues page
Create a new issue if your problem isn't already listed
Contact the maintainer at [lsolah23@somedom.com]

 
