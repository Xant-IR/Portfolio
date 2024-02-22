# Magic Library Website

The Magic Library Website is a robust e-commerce platform developed to specialize in the sale of a wide variety of books. Utilizing a structured layered architecture including Core, MVC, and Persistence layers, the platform ensures efficient development and scalability.

## Key Features

- **Products:** Includes comprehensive tools for managing products, encompassing prices, categories, attributes, and tags.

- **Shopping Cart:** Enables customers to add products for future purchase; can be anonymized until the user logs in or registers, integrating seamlessly with their existing cart.

- **Discounts:** Implements dynamic discount options for products, categories, and via discount coupons.

- **Product Comments and Ratings:** Enables users to leave comments and rate products according to their experience.

- **Orders and Payments:** Features streamlined processes for placing orders and facilitating secure payment transactions.

- **Automatic Order Cancellation:** Implemented an automated system to cancel unpaid orders if payment is not received within 24 hours, enhancing order management efficiency and inventory accuracy.

- **Wishlist:** Facilitates users in creating and managing their personalized list of preferred products.

- **Media Gallery:** Provides an exclusive customized media gallery for managing images and various media files efficiently.

- **SMS Notification:** Integrated SMS notifications to promptly inform customers about order placements and for authentication purposes.

- **Website Settings:** Settings management is simplified through a key-value pair system, enabling easy configuration of payment gateways, contact information, and visibility of SMS credit counts.

- **User Roles and Permissions:** Establishes diverse user roles with specific access permissions, ensuring precise control over platform access.

- **User Registration and Login:** Customers can easily register and log in, with access tailored to their respective roles.

- **Contact Section:** Incorporates a user-friendly contact form for seamless communication and inquiries.

- **Blog:** Hosts a dynamic blogging platform complete with categories, posts, comments, and tagging functionalities.

- **Website Statistics:** Offers valuable insights into website traffic and detailed product analytics.

- **Settings:** Allows for easy management of configuration settings to tailor the platform according to specific needs.

## Key Highlights

- Utilized a structured layered architecture including Core, MVC, and Persistence layers for efficient platform development.
- Developed a robust e-commerce platform specializing in the sale of a wide variety of books.
- Integrated a multi-vendor support feature, enabling diverse sellers to participate on the platform.
- Implemented two panels, one for administrators and one for customers, ensuring a seamless user experience for both.
- Introduced dynamic discount options to engage and incentivize customers, thereby enriching their shopping experience and encouraging repeat purchases.
- Incorporated a range of statistical tools to provide valuable insights for data-driven decision-making and efficient inventory management.
- Leveraged an existing Instagram following of over 50,000 followers to boost the online presence and contribute to rapid and exponential sales growth.

## Software Architecture

The Magic Library Website follows a layered architecture, including the following layers:

- **Core Layer:** Contains the core business logic and domain models of the application.
  
- **MVC (Model-View-Controller) Layer:** Responsible for handling user requests, rendering views, and interacting with the Core layer to execute business logic.
  
- **Persistence Layer:** Handles data storage and retrieval using a repository pattern. Utilizes Entity Framework Core for ORM (Object-Relational Mapping) and interacts with the underlying database. 
  
### Design Patterns

- **Repository Pattern:** Used to abstract data access logic and provide a consistent interface for interacting with data sources.
  
- **Unit of Work Pattern:** Coordinates multiple repository operations within a single transaction, ensuring data integrity and consistency.

### Testing

The Magic Library Website includes both unit tests and integration tests to ensure the reliability and functionality of the application. The tests cover various components of the platform, including controllers and repositories.

## Used Technologies

The  Magic Library Website is developed using the following technologies:

- **Backend:**
   - ASP.NET Core
   - Entity Framework Core (EF Core)
   - SQL Server
   - C#
   - Elmah
   - AutoMapper
   - FluentAssertions
   - Moq
   - NUnit
   - DNTCommon.Web.Core
   - Parbad
   - Shyjus.BrowserDetector
   - WebMarkupMin.AspNetCore
   - LigerShark.WebOptimizer.Core
   - SixLabors.ImageSharp
   
- **Frontend:**
   - HTML
   - CSS
   - JavaScript
   - Bootstrap
   - jQuery
   - jQuery DataTables
   - jQuery Validation
   - jQuery Confirm
   - Dropzone
   - DataPicker
   - Jalali Moment
   - Select2
   - Shave JS
   - CKEditor
   - Font Awesome

## Screenshots

Here are some screenshots of the Magic Library Website:

1. **Main Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/front-main.png"/>

2. **Products Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/front-products.png"/>

3. **Single Product Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/front-products-single.png"/>

4. **Shopping Cart Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/front-cart.png"/>

5. **Dashboard - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/admin-panel-dashboard.png"/>

6. **Product Creation View - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/admin-panel-products-single.png"/>

7. **Dashboard - Customer Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/08.MagicLibraryWebsite/screenshots/customer-panel-dashboard.png"/>
