# CODE-ALPHA-INTERNSHIP-STOCK-PORTFOLIO-TRACKER

## Project Explanation: Stock Portfolio Tracker

This project is a beginner-friendly Python application that helps users track their stock investments by calculating the total value of their portfolio based on predefined stock prices.

### Purpose

The tracker simplifies investment monitoring by allowing users to manually enter stock holdings and instantly see the total monetary value of their investments without needing real-time API access.

### How It Works

1. **Stock Price Dictionary**: The program uses a hardcoded Python dictionary (`STOCK_PRICES`) containing 8 popular stocks (AAPL, TSLA, GOOGL, MSFT, AMZN, NVDA, META, NFLX) with their respective prices.

2. **User Input**: Users interactively enter stock symbols and the number of shares they own. The program validates inputs to ensure only valid symbols and positive quantities are accepted.

3. **Calculation**: For each stock, the program multiplies quantity by price to get individual holding values, then sums them for the total portfolio value.

4. **Display**: A formatted table shows each stock's symbol, quantity, price, and calculated value, followed by the total investment amount.

5. **File Export**: Users can save their portfolio summary to either a `.txt` file (formatted report) or `.csv` file (spreadsheet-compatible) for future reference.

### Key Programming Concepts

- **Dictionaries**: Store and retrieve stock prices efficiently
- **Input/Output**: Handle user interactions and display results
- **Arithmetic Operations**: Calculate investment values
- **File Handling**: Write data to external files
- **Error Handling**: Validate user inputs gracefully
- **Functions**: Organize code into reusable, logical blocks

### Ideal For

This project is perfect for Python beginners learning fundamental concepts while building something practical they can actually use to track hypothetical or real stock portfolios.
