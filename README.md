# React Currency Converter

This project is a React-based Currency Converter application that allows users to convert amounts between different currencies using real-time exchange rates.

## Features

- **Convert Between Currencies**: Users can input an amount, select the source and target currencies, and convert between them.
- **Dynamic Currency List**: Fetches and displays a list of available currencies using an external API.
- **Swap Functionality**: Easily swap between the source and target currencies.
- **Responsive Design**: Works well on both desktop and mobile devices.

## File Structure

```
CurrencyConvertor/
├── public/               # Static files
├── src/                  # Source code
│   ├── components/       # Reusable React components
│   │   ├── InputBox.jsx  # Input component for currency conversion
│   ├── hooks/            # Custom hooks
│   │   ├── useCurrencyInfo.js  # Hook to fetch currency data
│   ├── App.jsx           # Main application component
│   ├── index.css         # Global styles
│   ├── main.jsx          # Application entry point
├── package.json          # Project dependencies and scripts
├── README.md             # Project documentation
```

## API Used

This application fetches currency data from:
[Currency API by @fawazahmed0](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api/)

## How to Use

1. Enter an amount in the "From" field.
2. Select the source and target currencies from the dropdowns.
3. Click the **Convert** button to view the converted amount.
4. Use the **Swap** button to switch the source and target currencies.

## Example

- Convert 100 USD to INR:
  ```
  From: 100 USD
  To: INR
  Result: 8300.50 INR (based on the current exchange rate)
  ```

## Technologies Used

- **React**: Frontend framework.
- **Tailwind CSS**: For styling.
- **JavaScript**: For logic and interactivity.
- **Currency API**: For fetching real-time currency exchange rates.


 
