# Batalent Startup Platform

The Batalent Startup Platform is a comprehensive online platform aimed at introducing businesses and their services, showcasing their work background, and facilitating communication and transactions with potential clients in the domestic market. The platform boasts several key features designed to enhance user experience and streamline business operations.

## Key Features

- **Subscriptions:** Businesses can purchase subscriptions, receive notifications upon expiry, hide media when subscriptions expire, avail regular and discounted prices, and opt for free subscriptions with a 100% discount.

- **Discounts:** Various discount options include time-limited, usage-limited, and code-based discounts, available in both monetary and percentage formats. Discounts can be applied multiple times, with the latest discount taking precedence. Support for discount codes is provided, and directly applied discounts are given priority.

- **Purchase and Payment:** Subscriptions can be purchased through the business panel, with integrated payment gateways facilitating secure transactions. Free orders are processed without the need for a gateway connection, and subscriptions are activated immediately upon successful payment.

- **Uploaded Media or Files:** Uploaded files are categorized and stored systematically, with a dedicated admin-managed media gallery ensuring efficient file management. Each file is assigned a unique filename generated automatically.

- **User Comments:** Users can leave comments under business pages, which are subject to approval by the business owner. Comment threads support replies and are displayed hierarchically. User IPs are logged for security purposes.

- **User Ratings:** Users can rate businesses on a scale of 0 to 5, with each user allowed to rate a business only once. The average rating for each business is displayed on their respective pages.

- **Website Settings:** Settings management is simplified through a key-value pair system, enabling easy configuration of payment gateways, contact information, and visibility of SMS credit counts.

- **Sliders:** Image sliders are dynamically managed, allowing for the inclusion of multiple images with adjustable display order.

- **Grid Squares:** A versatile grid square feature accommodates various content types, including images, videos, and links, organized with customizable item arrangements.

- **Users and Roles:** The system supports multiple user roles, including Regular Users and Professional Business Users, each with tailored panel access and predefined permissions.

- **User Registration and Login:** Users can register and log in using a one-time verification code sent via SMS, choosing between roles such as "Regular User" or "Professional User or Business." Password recovery and change functionalities are available for added security.

- **Static Pages:** The website includes dynamically generated static pages containing essential content like privacy policies, terms, and an about us section, all managed conveniently via the admin panel.

- **Forms:** Users can utilize various forms such as contact us, collaboration request, and error reporting, with the option to upload resume files. Account details are automatically included during form submission if the user is logged in.

- **Services:** Businesses can offer a range of services, from restaurants to event halls, connected to relevant events, providing flexibility in selection and association.

- **Events:** Events like weddings and birthdays are seamlessly linked to relevant services, allowing businesses to select and associate with multiple events.

- **Businesses (Professional Users):** Professional users can maintain their profiles and portfolios on the platform through subscriptions, enabling media uploads and ensuring visibility of content with an active subscription.

- **Contact Requests:** Users can initiate contact requests directly from business pages, choosing between standard or high-priority options. Submissions trigger SMS notifications for prompt response.

- **Dynamic Blog Posts:** Engineered flexible blogging capabilities tailored specifically for creating, managing, and interacting with blog posts, supporting categories, comments, and tags for enhanced user engagement and content organization.

- **Website Statistics:** Detailed website statistics, including user IPs, visited paths, browsers, and countries, along with business-specific visit statistics, are available for comprehensive analysis in the admin panel.

- **Additional Key Features:**
  - Developed a fully functional media gallery using JavaScript and API backend to upload and load different file types in the panels with the option to integrate media gallery to input files and CKEditor.
  - Utilized OpenLayers map to display business company locations, enhancing user navigation and project visibility.

## Key Highlights

- Utilized a layered architecture, comprising Core, MVC, Persistence, and Services layers, for a well-structured and efficient platform.
- Developed a fully functional platform to introduce the businesses and their services and to exhibit their work background to potential clients in the domestic market.
- Improved the whole procedure of finding businesses, communicating with them, and ordering their products or services for clients.
- Implemented a custom subscription management system so that businesses should pay monthly/yearly charges to maintain their profile and portfolio on the platform.
- Designed three distinct panels - Admin, Business, and Clients - providing specialized functionalities.
- Configured server installations and successfully deployed the platform, ensuring its accessibility to users.

## Software Architecture

The Batalent Startup Platform follows a layered architecture, including the following layers:

- **Core Layer:** Contains the core business logic and domain models of the application.
  
- **MVC (Model-View-Controller) Layer:** Responsible for handling user requests, rendering views, and interacting with the Core layer to execute business logic.
  
- **Persistence Layer:** Handles data storage and retrieval using a repository pattern. Utilizes Entity Framework Core for ORM (Object-Relational Mapping) and interacts with the underlying database.
  
- **Services Layer:** Provides additional business logic and services beyond what is offered in the Core layer. This layer enhances the scalability and flexibility of the platform.
  
### Design Patterns

- **Repository Pattern:** Used to abstract data access logic and provide a consistent interface for interacting with data sources.
  
- **Unit of Work Pattern:** Coordinates multiple repository operations within a single transaction, ensuring data integrity and consistency.

### Testing

The Batalent Startup Platform includes both unit tests and integration tests to ensure the reliability and functionality of the application. The tests cover various components of the platform, including controllers, repositories, and service layers.

## Used Technologies

The  Batalent Startup Platform is developed using the following technologies:

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
   
- **Frontend:**
   - HTML
   - CSS/SCSS
   - JavaScript
   - Bootstrap
   - jQuery
   - jQuery DataTables
   - jQuery Validation
   - OpenLayers
   - Swiper
   - Chart.js
   - Dropzone
   - Jalali Moment
   - SweetAlert2
   - Select2
   - Sortable JS
   - CKEditor
   - Font Awesome

## Screenshots

Here are some screenshots of the Batalent Startup Platform:

1. **Home Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/front-home.png"/>

2. **Single Business Page - Frontend**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/front-businesses-single.png"/>

3. **Dashboard - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/admin-panel-dashboard.png"/>

4. **Media Gallery - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/admin-panel-mediagallery.png"/>

5. **Single Grid Item View - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/admin-panel-griditem.png"/>

6. **Manual Business Registration - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/admin-user-registration.png"/>

7. **Dashboard - Business Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/business-panel-dashboard.png"/>

8. **Media Items View - Business Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/07.BatalentStartupPlatform/screenshots/business-panel-media.png"/>
