# Accounting System Application

Welcome to the Accounting System Application README! This comprehensive accounting software is tailored to meet the specific needs of businesses, providing efficient financial record-keeping, inventory management, and financial analysis tools.

## Key Features

- **Customized Accounting:** Tailored accounting features designed to meet the unique needs of businesses, ensuring flexibility and adaptability to various industries.
- **Financial Record-Keeping:** Efficient tools for recording financial transactions, managing accounts payable and receivable, and maintaining accurate financial records.
- **Inventory Management:** Comprehensive inventory management functionality to track products, monitor stock levels, and manage inventory costs effectively.
- **Financial Analysis:** Robust tools for financial analysis, including profit and loss statements, balance sheets, and cash flow analysis, providing valuable insights into business performance.
- **Enhanced Financial Control:** Streamlined processes and controls to enhance financial oversight and control within the organization, ensuring compliance and risk management.
- **Reporting Capabilities:** Improved reporting capabilities for comprehensive financial insights, enabling informed decision-making and strategic planning.
- **User Authentication:** Secure user authentication system with role-based access control to safeguard sensitive financial data and ensure authorized access to the application's features and functionalities.
- **Tax Management:** Built-in tax management features to configure and apply tax rates for purchases and sales transactions, ensuring compliance with tax regulations and simplifying tax reporting processes.
- **Product Management:** Comprehensive product management capabilities to track product details, including purchase price, sales price, quantities, units of measurement, and barcodes, enabling efficient inventory tracking and sales management.
- **Warehouse Management:** Integrated warehouse management features to optimize warehouse space, track inventory movement across multiple locations, and streamline order fulfillment processes for improved efficiency and customer satisfaction.
- **Group Management:** Flexible group management functionality to organize accounts, products, and other entities into logical groups, simplifying data organization and enhancing usability.
- **Deposit Management:** Efficient management of deposits into accounts, including recording deposit details, such as account numbers, customer names, amounts, and deposit dates, for accurate tracking and reconciliation of financial transactions.
- **Settings Configuration:** Easy-to-use settings configuration options to customize application settings, including shop name, contact information, addresses, descriptions, and images, to align with business preferences and branding requirements.

## Key Highlights

- Engineered a tailored accounting application for a wood company, increasing operational efficiency by 25%.
- Facilitated efficient financial record-keeping within the application, reducing data entry time by 30%.
- Implemented features for inventory management to track wood products.
- Provided tools for financial analysis, contributing to informed decision-making.
- Contributed to enhanced financial control through streamlined processes.
- Improved reporting capabilities for comprehensive financial insights.

## Database Schema

The Accounting System Application utilizes a SQL database with the following schema:

- **Income:** Manages income records, including income name, account number, account name, registration date, amount, and description.
- **Contact:** Stores contact information for clients or suppliers, including contact name, telephone, mobile, and address.
- **PaymentCheck:** Tracks payment checks issued by the organization, including check number, account number, account name, amount, registration date, recipient, customer name, status, and description.
- **ReceivedCheck:** Manages received checks, including check number, account number, account name, amount, registration date, recipient, customer name, status, and description.
- **Warehouse:** Stores information about warehouse locations and inventory management.
- **PurchaseInvoice:** Manages purchase invoices, including invoice number, date, supplier name, item details, purchase amount, taxes, and total amount.
- **SalesInvoice:** Tracks sales invoices issued by the organization, including invoice number, date, customer name, item details, sales amount, taxes, and total amount.
- **Expense:** Records expenses incurred by the organization, including expense name, account number, account name, registration date, amount, and description.
- **Account:** Stores account information, including account number, account name, account type, balance, and description.
- **PaymentFromAccount:** Records payments made from accounts, including account number, account name, customer name, amount, payment date, description, and customer ID.
- **Customer:** Stores customer information, including customer ID, customer name, customer type, telephone, mobile, receivable, and payable.
- **Tax:** Manages tax rates for purchases and sales.
- **User:** Stores user credentials for application authentication, including user ID, username, and password.
- **Product:** Manages product information, including product ID, product group name, product name, purchase price, sales price, quantity, unit, and barcode.
- **WarehouseSpace:** Manages warehouse space information, including warehouse ID, product name, from, quantity, warehouse name, and date.
- **Groups:** Manages group information, including group ID and group name.
- **DepositToAccount:** Logs deposits into accounts, including deposit ID, account number, account name, customer name, amount, deposit date, description, and customer ID.
- **Settings:** Stores settings related to sales, including shop name, telephone, mobile, address, description, and image.

## Stored Procedures

The database incorporates a set of stored procedures specifically designed to facilitate the generation of detailed reports, offering users comprehensive insights into various aspects of the accounting system's operations and financial transactions. 

## Reporting

Reporting functionality in the Accounting System Application is supported by Stimulsoft Reports, equipping users with robust tools to generate and tailor reports for analyzing financial data and business performance.

## Used Technologies

The Accounting System Application is developed using the following technologies:

- **Programming Language:** C#
- **Application Type:** Windows Forms
- **Database Management System:** SQL Server
- **Reporting Tool:** Stimulsoft Reports
- **Other Technologies:** .NET Framework, DevComponents.DotNetBar

## Screenshots

Here are some screenshots of the Accounting System Application:

1. **Main Form**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/02.DesktopApplicationDevelopment/02.AccountingSystemApplication/screenshots/main.png"/>

2. **Product Form**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/02.DesktopApplicationDevelopment/02.AccountingSystemApplication/screenshots/product.png"/>

3. **Contact List**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/02.DesktopApplicationDevelopment/02.AccountingSystemApplication/screenshots/contact.png"/>

4. **Sales Invoices List**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/02.DesktopApplicationDevelopment/02.AccountingSystemApplication/screenshots/sales-invoice.png"/>

5. **Income List**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/02.DesktopApplicationDevelopment/02.AccountingSystemApplication/screenshots/income.png"/>
