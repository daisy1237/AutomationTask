# Demoblaze Shopping Automation – UiPath

An **RPA project built with UiPath Studio**, automating the shopping process on [Demoblaze](https://www.demoblaze.com/), a demo website.

## Features

- **Browser Management:** Opens Chrome in Incognito mode and manages browser sessions.
- **Authentication:** Handles login, logout, and user verification.
- **Product Selection:** Filters products by category, brand, and price, selecting the most expensive matching product.
- **Cart Management:** Adds products, manages quantities, and validates cart contents and total price.
- **Excel Processing:** Reads and validates orders from Excel files and generates reports.
- **Order Placement:** Completes checkout and captures order confirmation screenshots.
- **Email Automation:** Sends order results and reports via email.
- **Exception Handling:** Handles system and business exceptions, sending user-friendly error notifications with screenshots attached.

## Exception Handling

The automation distinguishes between:

- **System Exceptions:** Technical failures such as missing UI elements, browser issues, or failed operations.
- **Business Rule Exceptions:** Invalid input data, incorrect quantities, invalid price ranges, or missing required information.

When an error occurs, the robot generates a user-friendly message, captures a screenshot as evidence, and sends an automated email notification.

## Technologies Used

- UiPath Studio (Classic Activities)
- VB.NET Expressions
- Microsoft Excel
- SMTP Email Automation
- Google Chrome

## How to Run

1. Clone the repository and open `project.json` in UiPath Studio.
2. Configure the required credentials and email settings.
3. Prepare the Excel file containing the orders.
4. Run `Main.xaml`.

## Notes

This project is intended for **educational purposes** and uses the Demoblaze demo website. No real purchases are performed.
