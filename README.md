# Currency Converter

Currency Converter is a simple Java application that allows users to convert between different currencies based on predefined exchange rates.

## Features

- Convert a specified amount from one currency to another.
- Supports a range of currencies, including INR, USD, EUR, GBP, CAD, AUD, JPY, CHF, CNY, HKD, KRW, MXN, NOK, NZD, SEK, SGD, THB, TRY, and ZAR.
- Provides real-time conversion results.
- User-friendly graphical user interface (GUI) built using Java Swing.

## Getting Started

### Prerequisites

To run the Currency Converter application, you need to have the following software installed on your machine:

- Java Development Kit (JDK) 8 or above
- Apache Maven (if using Maven for dependency management)

### Running the Application

1. Clone the repository or download the source code files.

## Usage
1.Enter the amount to convert in the "Amount" text field.
2.Select the currency you want to convert from in the "From" dropdown menu.
3.Select the currency you want to convert to in the "To" dropdown menu.
4.Click the "Convert" button to calculate the converted amount.
5.The result will be displayed in the "Result" text field.

## Customize Exchange Rates
If you want to customize or add additional exchange rates, you can modify the CURRENCIES and EXCHANGE_RATES arrays in the CurrencyConverter class. Update the currency symbols in the CURRENCIES array and the corresponding exchange rates in the EXCHANGE_RATES array.
private final String[] CURRENCIES = {"INR", "USD", "EUR", /* Add your currency symbols here */};
private final double[] EXCHANGE_RATES = {1, 84.24, 89.57, /* Add your exchange rates here */};


