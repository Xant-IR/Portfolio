# Tour Reservation Website

The Tour Reservation Website is a digital platform developed to simplify tour booking and management processes for travelers.

## Key Features

- **Multilingual Support:** Implemented multilingual support for enhanced accessibility across different markets.
- **Tour Organization:** Enabled seamless organization and booking of various travel and leisure tours.
- **Automatic Order Cancellation:** Implemented automatic order cancellation after 20 minutes of non-payment to streamline the booking process and maintain inventory accuracy.
- **Capacity Management:** Automatically makes tours unavailable after reaching full capacity, ensuring optimal tour experience and resource allocation.
- **Secure Payment Processing:** Prioritized security for online payments and refunds, ensuring customer trust and satisfaction.
- **SMS Notification:** Implemented SMS notifications to alert administrators when a new reservation for their tour is added, facilitating timely response and management.
- **Comprehensive Contact Details:** Contact information, including phone numbers, email addresses, and physical addresses, is prominently displayed on the website. This makes it easy for customers to connect with the company for inquiries or assistance.
- **Dynamic Blog Feature:** A dynamic blog feature is implemented to share company updates and industry insights with visitors. This feature helps in engaging the audience and establishing the company as an authority in the industry.

## Key Highlights

- Implemented a structured architecture comprising MVC, Core, Persistence, and Tests layers, ensuring scalability and maintainability.
- Developed a bilingual travel agency website to facilitate easy tour reservation and management.
- Enabled seamless organization and booking of diverse travel and leisure tours.
- Implemented multilingual support for seamless navigation and accessibility in diverse markets.
•- Ensured secure online payments and refunds for customer satisfaction.

## Software Architecture

The Tour Reservation Website project is structured into multiple layers including Core, MVC, Persistence, and Tests projects.

- **Core:** This layer contains the core business logic and domain models of the application.
  
- **MVC (Model-View-Controller):** Responsible for handling user requests, rendering views, and interacting with the Core layer to execute business logic.
  
- **Persistence:** Handles data storage and retrieval using a repository pattern. Utilizes Entity Framework Core for ORM (Object-Relational Mapping) and interacts with the underlying database.
  
- **Tests:** Includes unit tests and integrated tests for ensuring the reliability and functionality of the application.
  
### Design Patterns

- **Repository Pattern:** Used to abstract data access logic and provide a consistent interface for interacting with data sources.
  
- **Unit of Work Pattern:** Coordinates multiple repository operations within a single transaction, ensuring data integrity and consistency.

### Testing

- Controllers and repositories are unit tested using an in-memory database to simulate data interactions. 
- Integrated tests are performed to validate the functionality of the application components as a whole.

## Used Technologies

The Tour Reservation Website is developed using the following technologies:

- **Backend:**
   - ASP.NET Core
   - Entity Framework Core (EF Core)
   - SQL Server
   - C#
   - Elmah
   - DNTScheduler.Core
   - AutoMapper
   - Parbad
   - SmsIrRestful
   - FluentAssertions
   - Moq
   - NUnit
   
- **Frontend:**
   - HTML
   - CSS
   - JavaScript
   - Bootstrap
   - jQuery
   - jQuery DataTables
   - jQuery Validation
   - jQuery Confirm
   - CKEditor
   - Font Awesome
   - Light Gallery
   - Select2
   - Moment.js

## Screenshots

Here are some screenshots of the Tour Reservation Website:
