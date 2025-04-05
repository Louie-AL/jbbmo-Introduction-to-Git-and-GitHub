# Simple Interest Calculator

This project provides a simple interest calculator that computes the simple interest based on the principal amount, annual rate of interest, and time period in years.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [License](#license)
- [Code of Conduct](#code-of-conduct)
- [Contributing](#contributing)

## Features

- **Simple Interest Calculation:** Computes simple interest using the formula:
  ```
  simple interest = principal × time × rate
  ```
- **Compound Interest Calculation:** Computes compound interest using the formula:
  ```
  compound interest = principal × (1 + rate)^time - principal
  ```

## Usage

1. **Simple Interest Calculation:**
   - **Script:** `simple-interest.sh`
   - **Usage:** Run the script and input the principal amount, time period in years, and annual rate of interest when prompted.
   - **Example:**
     ```bash
     ./simple-interest.sh
     ```
     *Input:*
     ```
     Enter the principal amount: 1000
     Enter the time period in years: 5
     Enter the annual rate of interest: 5
     ```
     *Output:*
     ```
     The simple interest is: 250
     ```

2. **Compound Interest Calculation:**
   - **Script:** `compound_interest.py`
   - **Usage:** Run the script and input the principal amount, time period in years, and annual rate of interest when prompted.
   - **Example:**
     ```bash
     python compound_interest.py
     ```
     *Input:*
     ```
     Enter the principal amount: 1000
     Enter the time period in years: 5
     Enter the annual rate of interest: 5
     ```
     *Output:*
     ```
     The compound interest is: 276.28
     ```

## License

This project is licensed under the Apache-2.0 License. See the [LICENSE](LICENSE) file for more details.

## Code of Conduct

Please refer to the [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) file for the code of conduct guidelines.

## Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) file for guidelines on how to contribute to this project.
