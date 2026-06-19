# WealthFlow | Salary Tool (FY 2026)

This is a browser-based utility designed to calculate monthly and annual tax liabilities for salaried individuals in Pakistan. It is updated with the tax slabs for the last 5 fiscal years but allows users to adjust these brackets manually if regulations change.

## Key Features

* **Automatic Salary Breakdown**: If you only know your total gross salary, the tool can automatically generate an optimized split between Basic Salary, House Rent, Utilities, and Medical allowances.
* **Tax Slab Customization**: The tax brackets are pre-set based on current projections, but all rates and thresholds are editable to keep the tool relevant as laws update.
* **Provident Fund Logic**: Calculates both Employer and Employee contributions based on a percentage of the basic salary.
* **Exemptions**: Accounts for tax-exempt components like certain work expenses and medical allowances.
* **Currency Conversion**: Provides a real-time conversion of take-home pay into USD based on a user-defined exchange rate.

## Technical Details

The tool is built as a single-file application using standard web technologies:

* **HTML5/CSS3**: Handles the layout and responsive design.
* **Vanilla JavaScript**: Manages the calculation logic and DOM updates without any external dependencies or libraries.

### Calculation Logic

The tax calculation follows the standard progressive slab system used by the FBR. The "Generate" function uses common payroll industry standards (e.g., Basic Salary at roughly 60% of gross) to create a plausible breakdown for those who do not have their specific payroll details on hand.

## Privacy and Data

This tool is strictly client-side. No salary data is transmitted to a server, and no information is stored outside of your own browser's temporary session. It is safe for use with sensitive financial figures.
