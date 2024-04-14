This is a web application designed to calculate taxes based on user input. The application is implemented using HTML, CSS, and JavaScript, with the option to use Bootstrap and jQuery.

Overview
The Tax Calculator allows users to input their gross annual income, extra income, age group, and total applicable deductions to calculate their tax liability. The tax calculation follows specific rules based on income and age group, as outlined in the provided requirements.

Features
  Input Fields: Users can enter their gross annual income, extra income, age group, and total applicable deductions.
  Error Handling: The application handles various error cases, such as invalid input or missing fields, and provides visual feedback to the user.
  Tax Calculation: Based on the provided input, the application calculates the tax liability according to the specified rules.
  Modal Display: The calculated tax amount is displayed in a modal window for easy viewing.

Usage
1. Input Fields: 
  Gross Annual Income: Enter the total income before any deductions.
  Extra Income: Input any additional income apart from the annual income.
  Age Group: Select the appropriate age group from the dropdown menu.
  Total Applicable Deductions: Enter the amount that can be subtracted from the gross income to reduce taxable income.

2. Error Handling:
  If any of the input fields contain invalid data or are left empty, error icons will be displayed next to the respective fields. Hovering over these icons will reveal tooltips with error messages.
  The application ensures that the user can input any character in the fields, but if non-numeric characters are entered in the number fields, an exclamation mark will appear to indicate the error.

3. Tax Calculation:
  Upon clicking the "Calculate Tax" button, the application calculates the tax liability based on the provided input.
  The tax amount is displayed in a modal window for the user to review.

Assumptions
  The application allows users to input any character in the number fields but indicates errors if non-numeric characters are entered.
  The design and layout of the application are flexible and can be modified as needed, as long as all functionalities and requirements are met.
  All edge cases, such as empty fields or invalid input, are handled to ensure a smooth user experience.

Requirements
  Web browser with JavaScript enabled.
  Internet connection (if accessing online).

Limitations
  The application is designed for demonstration purposes and may not accurately reflect real-world tax calculations.
  It is recommended to verify the calculated tax amounts with a certified tax professional for accurate results.
