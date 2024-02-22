# Build&Enjoy Startup Platform

The Build&Enjoy Startup Platform offers a comprehensive solution for streamlined project outsourcing in construction and renovation sectors, featuring a modular architecture, specialized user panels, and a diverse range of features for project management and offer submissions.

## Key Features

- **Businesses Profile Management:** Businesses can manage their profiles, including photos, information, comments, offers to clients, and supporting documents.

- **Client Interaction:** Clients can communicate with businesses through the platform, including sending messages and receiving offers.

- **Project Management:** Clients can submit renovation or construction projects, detailing project specifications and requirements.

- **Project Offers:** Businesses can submit offers for projects, allowing clients to review and accept offers.

- **Project Reports:** Businesses can send project reports to clients, keeping them updated on project progress.

- **Checklist Management:** Projects can include checklists for businesses to follow, ensuring project requirements are met.

- **Membership Subscription:** Businesses can subscribe to membership plans for full access to profile features.

- **Advertisements:** Businesses can promote products/services via platform ads, featuring a picture and link for effective audience targeting.

- **Wishlist Functionality:** Users can create and manage wishlists for future projects or services.

- **Discounts:** Provide versatile discount options including time-limited, usage-limited, and code-based discounts, prioritizing the latest discount, with support for discount codes.

- **Purchase and Payment:** Securely purchase subscriptions and process free orders via integrated payment gateways, with instant activation upon payment success.

- **Users and Roles:** The system supports multiple user roles, including Client Users and Business Users, each with tailored panel access and predefined permissions.

- **User Registration and Login:** Users can register and log in using email verification or Google Authentication, choosing between roles such as "Client User" or "Business User" Password recovery and change functionalities are available for added security.

- **Uploaded Media or Files:** Efficiently manage uploaded files with a dedicated admin-managed media gallery, ensuring systematic categorization and unique filenames for each file.

- **User Comments:** Enable user interaction through comments on business pages, moderated by business owners, with hierarchical thread displays and IP logging for security.

- **Website Settings:** Settings management is simplified through a key-value pair system, enabling easy configuration of payment gateways, contact information, and visibility of SMS credit counts.

- **Forms:** Users can utilize contact us and collaboration request forms to get in touch with the startup administrators.

- **Dynamic Blogging:** Created versatile blogging capabilities encompassing categories, posts, comments, and tags, serving both news updates and regular blog content across distinct sections.

- **Website Statistics:** Detailed website statistics, including user IPs, visited paths, browsers, and countries, along with business-specific visit statistics, are available for comprehensive analysis in the admin panel, while businesses can also track profile views in their panel.

- **Additional Key Features:**
  - Developed a fully functional media gallery using JavaScript and API backend to upload and load different file types in the panels with the option to integrate media gallery to input files and CKEditor.
  - Integration with Google Analytics to track and analyze website traffic patterns, user interactions, and overall user behavior for informed decision-making and performance optimization.
  - Automated order cancellation for unpaid orders after a specified period, along with subscription/advertisement deactivation upon expiration.
  - Utilized OpenLayers map to display locations of renovation/construction projects and business company locations, enhancing user navigation and project visibility.
  - Integrated Google Maps to showcase the startup owner's company location, providing a convenient reference point for users.
  - Created a customized multi-step form using JavaScript, implementing validation at each step and enabling seamless submission to the server for renovation/construction project submission.

## Key Highlights

- Implemented a layered Architecture, ensuring systematic organization into Core, MVC, and Persistence layers for enhanced modularity and simplicity.
- Streamlined the outsourcing process for construction and renovation projects via an intuitive and user-friendly platform.
- Engineered and integrated key features such as subscription management, project request/offer mechanisms, checklist management, and report handling mechanisms.
- Developed specialized panels for Admin, Business, and Clients, offering tailored functionalities to meet the diverse needs of each user group.
- Facilitated efficient project management through automated mechanisms, enabling seamless communication and collaboration among stakeholders.
- Ensured a well-structured and efficient platform design, fostering optimal user experience and operational efficiency.

## Software Architecture

The Build&Enjoy Startup Platform follows a layered architecture, including the following layers:

- **Core Layer:** Contains the core business logic and domain models of the application.
  
- **MVC (Model-View-Controller) Layer:** Responsible for handling user requests, rendering views, and interacting with the Core layer to execute business logic.
  
- **Persistence Layer:** Handles data storage and retrieval using a repository pattern. Utilizes Entity Framework Core for ORM (Object-Relational Mapping) and interacts with the underlying database.
  
- **Services Layer:** Provides additional business logic and services beyond what is offered in the Core layer. This layer enhances the scalability and flexibility of the platform.
  
### Design Patterns

- **Repository Pattern:** Used to abstract data access logic and provide a consistent interface for interacting with data sources.
  
- **Unit of Work Pattern:** Coordinates multiple repository operations within a single transaction, ensuring data integrity and consistency.

### Testing

The Build&Enjoy Startup Platform includes both unit tests and integration tests to ensure the reliability and functionality of the application. The tests cover various components of the platform, including controllers, repositories, and service layers.

## Used Technologies

The Build&Enjoy Startup Platform is developed using the following technologies:

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
   - Stripe.net
   - Shyjus.BrowserDetector
   - WebMarkupMin.AspNetCore
   - LigerShark.WebOptimizer.Core
   - Microsoft.AspNetCore.Authentication.Google

- **Frontend:**
   - HTML
   - CSS/SCSS
   - JavaScript
   - Bootstrap
   - jQuery
   - jQuery DataTables
   - jQuery Validation
   - OpenLayers
   - Chart.js
   - Dropzone
   - Jalali Moment
   - SweetAlert2
   - Select2
   - Shave
   - tempus-dominus
   - CKEditor
   - Font Awesome

## Screenshots

Here are some screenshots of the Batalent Startup Platform:
