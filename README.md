# Currency Conversion Application

This command-line application allows users to convert an amount from one currency to another using predefined conversion rates. The application prompts users to select the source and target currencies and enter the amount they want to convert.

## Features

- Convert between PKR, USD, and GBP currencies.
- User-friendly prompts for currency selection and amount input.
- Displays the converted amount based on current conversion rates.

## Requirements

- Node.js
- `inquirer` package

## Installation

1. Clone this repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the project directory:

   ```bash
   cd <project-directory>
   ```

3. Install the required dependencies:

   ```bash
   npm install
   ```

## Usage

1. Run the application:

   ```bash
   node index.js
   ```

2. Follow the prompts:
   - Select the source currency.
   - Select the target currency.
   - Enter the amount to be converted.

3. The application will display the converted amount.

## Code Explanation

- **Currency Conversion Rates**: The `Convertion` object stores conversion rates between PKR, USD, and GBP.
- **Prompts**: Uses `inquirer` to get user input for source currency, target currency, and amount.
- **Conversion Calculation**: Calculates the converted amount using the selected currencies and conversion rates.
- **Validation**: Checks if all inputs are provided and performs the conversion.

## Example

```bash
Select your currency: PKR
Select your conversion currency: USD
Enter your conversion amount: 1000
Your conversion from PKR to USD is 4.4
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

*This project was completed on March 28 at approximately 3:00 AM.*
```

