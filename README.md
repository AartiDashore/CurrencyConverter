# Currency Converter

Currency Converter using Forex Python Module

## Introduction

This is a simple currency converter implemented in Python using the Forex Python module. The program allows users to convert between different currencies based on the latest exchange rates provided by the Forex Python module.

## Features

- **Currency Conversion:** Convert from one currency to another using the latest exchange rates.
- **Up-to-date Exchange Rates:** The program fetches the latest exchange rates from the Forex Python module, ensuring accurate and current conversions.
- **User-Friendly Interface:** The program provides a simple command-line interface for easy interaction.

## Requirements

Make sure you have the following dependencies installed:

- Python 3.x
- Forex Python module (`forex-python`)

You can install the required module using the following command:

```bash
pip install forex-python
```

## Usage

1. Clone the repository or download the source code.

```bash
git clone https://github.com/your-username/currency-converter.git
cd currencyconverter
```

2. Run the program:

```bash
python currencyconverter.py
```

3. Follow the on-screen instructions to input the amount, source currency, and target currency.

4. The program will display the converted amount based on the latest exchange rates.

## Example

```bash
python currencyconverter.py
```

```
Welcome to the Currency Converter!

Enter the amount: 100
Enter the source currency code (e.g., USD): USD
Enter the target currency code (e.g., EUR): EUR
100.0 USD is equal to 93.72 EUR
```

## Note

- The exchange rates are fetched in real-time using the Forex Python module, and the accuracy of the conversions depends on the reliability of the provided rates.

## License

This Currency Converter is open-source software licensed under the [MIT License](LICENSE).

## Contribution

Feel free to contribute to the project by opening issues or submitting pull requests. Your feedback and contributions are highly appreciated!
