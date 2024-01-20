# FinancialPy Package - FE 520B

## Overview

The FinancialPy package is a Python library designed for financial calculations related to present value, future value, annuities, perpetuities, cash flow analysis, and more. It provides a set of functions that can be easily used for various financial calculations, making it a valuable tool for financial analysts, investors, and anyone involved in financial planning.

## Installation

To use FinancialPy, you need to install the package. You can do this using the following command:

` pip install FinancialPy`

## Usage

Once installed, you can import the package and use its functions. Each function is called using `finpy.functionname()`. Below is a list of functions along with their descriptions and use cases:

### Present Value (pv_one)

`finpy.pv_one(fv, rate, periods)`

-Inputs:
*fv: Future value of the investment
*rate: The rate at which interest is compounded
*periods: Number of time periods the investment will be held for
-Use case:
*Calculate the present value of an investment given the future value, interest rate, and time period.

### Future Value (fv_one)

`finpy.fv_one(pv, rate, periods)`

-Inputs:
*pv: Present value of the investment
*rate: The rate at which interest is compounded
*periods: Number of time periods the investment will be held for
-Use case:
*Determine the future value of an investment based on present value, interest rate, and time period.

### Ordinary Annuity Present Value (pv_ordinary_annuity)

`finpy.pv_ordinary_annuity(pmt, rate, periods)`

-Inputs:
*pmt: Payment amount
*rate: The rate at which interest is compounded
*periods: Number of time periods the investment will be held for
-Use case:
*Calculate the present value of an ordinary annuity.

### Ordinary Annuity Future Value (fv_ordinary_annuity)

`finpy.fv_ordinary_annuity(pmt, rate, periods)`

-Inputs:
*pmt: Payment amount
*rate: The rate at which interest is compounded
*periods: Number of time periods the investment will be held for
-Use case:
*Determine the future value of an ordinary annuity.

...and many more

## Examples

Here are some examples demonstrating the usage of FinancialPy:

````import FinancialPy as finpy

# Example 1: Present Value Calculation
pv_value = finpy.pv_one(10000, 0.10, 5)
print(f"Present Value: {pv_value}")

# Example 2: Future Value Calculation
fv_value = finpy.fv_one(1000, 0.10, 5)
print(f"Future Value: {fv_value}")

# Example 3: Ordinary Annuity Present Value
pv_annuity = finpy.pv_ordinary_annuity(1000000, 0.08, 30)
print(f"Present Value of Annuity: {pv_annuity}")

# Example 4: Ordinary Annuity Future Value
fv_annuity = finpy.fv_ordinary_annuity(10000, 0.10, 30)
print(f"Future Value of Annuity: {fv_annuity}")```


## Contribution
Contributions to the FinancialPy package are welcome. Feel free to submit bug reports, feature requests, or pull requests on the GitHub repository.

## License
** This project is licensed under the MIT License - see the LICENSE file for details.**
````
