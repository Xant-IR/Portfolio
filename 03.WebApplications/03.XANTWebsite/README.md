# XANT Website

This project involves the development of an online digital agency website catering to the Iranian market, offering a comprehensive range of digital services.

## Key Features

- **Blog Functionality:** Incorporates a blog feature for sharing insights and updates, enhancing engagement with visitors by enabling the team to publish articles directly on the website.
- **Contact Form Integration:** Seamlessly integrates a contact form for client inquiries and messages, ensuring effective communication by securely storing submissions.
- **Portfolio Showcase with Categorization:** Showcases the company's portfolio, categorized for easy navigation, allowing visitors to explore projects by category and highlighting the company's expertise.

## Key Highlights

- Developed an online digital agency website, serving the Iranian market with a comprehensive range of digital services.
- Developed a user-centric, responsive website for easy access to services, portfolios, and information, ensuring optimal user experience.
- Included a portfolio showcase to highlight past projects and demonstrate the quality of work.
- Integrated interactive elements such as contact forms and social media links to enhance user engagement.
- Optimized performance for fast loading times and improved SEO rankings.

## Software Architecture

The XANT Website project is structured into multiple layers including Core, MVC, Persistence, and Tests projects.

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

## Database Schema

The XANT Website project utilizes a SQL Server database with the following schema:

- **AspNetRoleClaims:** Stores role claims for ASP.NET Identity.
- **AspNetRoles:** Contains roles for ASP.NET Identity.
- **AspNetUserClaims:** Stores user claims for ASP.NET Identity.
- **AspNetUserLogins:** Manages external logins for ASP.NET Identity.
- **AspNetUserRoles:** Maps users to roles in ASP.NET Identity.
- **AspNetUsers:** Stores user information for ASP.NET Identity.
- **AspNetUserTokens:** Manages authentication tokens for users in ASP.NET Identity.
- **Contacts:** Stores contact form submissions, including full name, email or phone number, subject, message body, IP address, and creation date.
- **PostCategories:** Contains categories for posts with title, creation date, and last edit date.
- **PostComments:** Manages comments on posts, including parent ID, user ID, post ID, user full name, email, comment body, IP address, status, creation date, last edit date, and edit status.
- **Posts:** Stores posts with title, body, creation date, last edit date, tags, category ID, user ID, comment status, and file path GUID.
- **Settings:** Stores various settings for the website, such as phone numbers, email addresses, addresses, social media URLs, and other contact information.

## Used Technologies

The XANT Website is developed using the following technologies:

- **Backend:**
   - ASP.NET Core
   - Entity Framework Core (EF Core)
   - SQL Server
   - C#
   - Elmah
- **Frontend:**
   - HTML
   - CSS
   - JavaScript
   - Bootstrap
   - jQuery
   - jQuery DataTables
   - jQuery Validation
   - CKEditor
   - Font Awesome
   - Tagger
   - Shave

## Screenshots

Here are some screenshots of the XANT Website:

1. **Database Diagram**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/03.XANTWebsite/screenshots/db-diagram.png"/>

2. **Home Page - Frontend**<br/>
  <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/03.XANTWebsite/screenshots/front-main.png"/>

3. **Portfolio Page - Frontend**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/03.XANTWebsite/screenshots/front-portfolio.png"/>

4. **Dashboard - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/03.XANTWebsite/screenshots/panel-dashboard.png"/>

5. **Single Portfolio View - Admin Panel**<br/>
   <img src="https://github.com/Xant-IR/Portfolio/blob/main/03.WebApplications/03.XANTWebsite/screenshots/panel-post-single.png"/>
