# Project: SubClub - The Sublet Management App

## Project Description:

### Overview

SubClub's inspiration comes from the housing challenges faced by individuals in Victoria, where the demand for affordable housing continues to grown. Witnessing the struggles of friends and acquaintances dealing with housing issues made me realise the need for rational solutions.

SubClub was born out of a desire to empower both potential subletters and those already involved in subletting. Based on personal experience and conversations with individuals grappling with the complexities of subletting, this web application aims to simplify the process of contract management and maintain transparent financial records.


### Problem Statement
The State of Victoria is experiencing a severe and continual rental crisis. This is marked by contributing factors that are making housing less affordable for renters.

Contributing factors may include:

The fall in supply due to lack of construction of new homes and dwellings
The lack of buildings repurposed for residential living
Increased taxes on investors, which has driven investors out from the residential market meaning more housing stock is being bought by owner occupiers. This in turn is negatively impacting the number of available rental properties on the market.
Increasing costs of energy impact the cost of living
Increased positive net migration driving up further demand in the rental market
Reduction to the total available medium to long term housing stock as homes have been repurposed for short-term stays (on a scale of days to weeks) for holiday and vacation rentals. E.g. AirBnB and Stayz
Increased cash rates from the Reserve Bank of Australia

As a result, more individuals are turning to shared living arrangements to cope with the housing demand. Many of these individuals (subletters and owner-occupiers with one or more unoccupied rooms or granny flats) are time poor and lack the experience needed to efficiently manage the subletting of their spare rooms to share the burden of higher rents or interest rates.


### Solution Statement
Sub.club is a web application that is used by Subletters to address the challenges of subletting. The application provides  a comprehensive solution for individuals looking to rent out their rooms for medium to long term (3 to 12 months).

This web application streamlines the process of managing agreements, recording payments and creating payment receipts.


## Key features:

With the sub.club web app, subletters are able to:

* Register new user account.
* Login and logout of user account.
* Create, update and view rooms (with the description of the room features and what is included in the rent).
* Create, update and view sub-tenant information.
* Create, update and view room assignments (subtenant(s), room and a date range).
    * When a room assignment is created, a printable lease agreement is automatically generated. This contract is based on the agreement of both parties and describes what is included in the rent, such as utilities, items accompanying the room (if furnished), cleaning services and access to shared common areas.
* Create (Registrated) and view past payments.
    * When a payment is created in the system, a payments receipt is auto-generated and is print friendly.


## Target Audiences

* Owner occupiers 
* Tenants who have a lease agreement with their landlord that they can sublet.


## Tech Stack

1. **Backend:**
   - **Node.js:** A JavaScript runtime that allows you to execute JavaScript code on the server side. It's designed to be lightweight and efficient for building scalable web applications.
   - **Express.js:** A web application framework for Node.js that simplifies the process of building robust and scalable APIs.

2. **Frontend:**
   - **JavaScript:** A versatile programming language that is widely used for building interactive and dynamic web applications.
   - **ReactJS (create-react-app):** A JavaScript library for building user interfaces, particularly for single-page applications. `create-react-app` is a tool that sets up a React project with a sensible default configuration.

3. **Database:**
   - **MongoDB Atlas:** A fully-managed cloud database service for MongoDB. It allows you to store and retrieve data in a flexible, JSON-like format.

4. **Deployment Server:**
   - **Heroku:** A cloud platform as a service (PaaS) that enables developers to deploy, manage, and scale applications. Heroku simplifies the deployment process and provides a platform for hosting web applications.

   - **Netlify:** A platform for continuous deployment that automates the process of deploying and hosting frontend applications. It also provides features like serverless functions and CDN for improved performance.

5. **CSS Framework:**
   - **Tailwind CSS:** A utility-first CSS framework that provides low-level utility classes to build designs directly in your markup. It's highly customizable and allows for rapid UI development.

6. **Version Control:**
   - **GitHub:** A web-based platform for version control using Git. GitHub facilitates collaboration among developers, hosting code repositories, and managing project workflows.

7. **Project Management:**
   - **Trello:** A popular project management tool that uses boards, lists, and cards to organise tasks and collaborate with others. It provides a visual and flexible way to manage projects.

8. **Design Tools:**
   - **Figma:** A collaborative design tool that enables teams to create, share, and prototype designs. It is known for its real-time collaboration features and is widely used in UX/UI design.

### Optional

9. **User Authentication:**
   - **Firebase Authentication:** A service provided by Firebase that simplifies the process of authenticating users in your application. It supports various authentication methods, including email/password, social logins, and more. 




