# Expense Tracker Application - README

## Overview
This Expense Tracker is a simple web-based application designed to help users manage their finances by tracking their salary, expenses, and remaining balance. The application features an intuitive interface for adding expenses, displaying total expenses, and calculating the remaining balance.

## Features
- **Set Salary**: Input the total monthly salary.
- **Add Expenses**: Add expenses by specifying:
  - **Description** (Reason for the expense)
  - **Amount**
  - **Date**
  - **Category** (e.g., Food, Transportation, Entertainment, Utilities, Other)
- **Expense List**: View a list of added expenses with the option to delete any expense.
- **Summary**:
  - Displays the total amount spent.
  - Shows the remaining balance.

## How to Use
1. **Load the Page**:
   - The app starts by showing the "Enter Total Salary" input field.
   - Enter your total salary and click **Submit Salary**.

2. **Add Expenses**:
   - Fill in the required fields:
     - **Reason**: A brief description of the expense.
     - **Amount**: The amount spent.
     - **Date**: When the expense occurred.
     - **Category**: Select from the available categories.
   - Click **Add Expense** to add the expense to the list.

3. **View and Manage Expenses**:
   - All added expenses are displayed in a list format.
   - Each entry shows the description, amount, date, and category.
   - Click **Delete** next to any expense to remove it from the list.

4. **View Summary**:
   - The total amount spent and the remaining balance are updated dynamically after each expense.

## Folder/File Structure
### `index.html`
The main HTML file that contains the structure of the application.

### Inline CSS
Styling is included in the `<style>` block within the HTML document:
- **Responsive Layout**: Ensures the application adapts to different screen sizes.
- **Custom Styles**: A visually appealing background image, centered content, and styled buttons for user interaction.

### Inline JavaScript
The logic is included in the `<script>` block within the HTML document:
- **Functions**:
  - `submitSalary()`: Handles salary submission and initializes the application.
  - `addExpense()`: Validates input and adds a new expense.
  - `deleteExpense(index)`: Deletes an expense from the list by its index.
  - `renderExpenses()`: Updates the expense list dynamically.
  - `calculateRemainingBalance()`: Calculates the remaining balance after expenses.
- **Event Listeners**:
  - For button clicks and keypress events (Enter key support for submitting salary).

## Requirements
- A modern web browser with JavaScript enabled.
- Internet connection to load the background image if the URL is used.

## Deployment
- Simply open the `index.html` file in any browser to run the application.
- The application is self-contained and does not require a server.

## Future Enhancements
- Add persistent storage using `localStorage` or a backend database.
- Include graphs and charts for visualizing expenses by category.
- Support multi-user accounts or profiles.
- Add more categories and customization options for users.

## Author
- **Ms.Devi M**
- For feedback or suggestions, feel free to reach out!
