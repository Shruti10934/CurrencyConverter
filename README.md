# React Currency Converter

This project is a React-based Currency Converter application that allows users to convert amounts between different currencies using real-time exchange rates.

## Features

- **Convert Between Currencies**: Users can input an amount, select the source and target currencies, and convert between them.
- **Dynamic Currency List**: Fetches and displays a list of available currencies using an external API.
- **Swap Functionality**: Easily swap between the source and target currencies.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Prerequisites

To run this project, make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shruti10934/CurrencyConvertor.git
   ```

2. Navigate to the project directory:
   ```bash
   cd CurrencyConvertor
   ```

3. Install the dependencies:
   ```bash
   npm install
   ```

## Running the Application

1. Start the development server:
   ```bash
   npm start
   ```

2. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

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

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or feedback, feel free to reach out to [Shruti Kumari](https://github.com/Shruti10934).

 
