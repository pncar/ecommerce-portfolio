# e-Commerce in Express
This project is a self-built e-commerce platform created to deepen my fullstack web development skills, specially. It includes:
- A React frontend (built with Vite)
- An Express.js backend with MySQL 5.7
- Fully documented REST API via Swagger
Rather than using pre-built libraries or ORMs, most of the functionality — from authentication to product filtering — has been implemented manually. Some things, like handling seeding and migrations, were made with Knex.

## Features
- User Side:
  - User registration and login (JWT-based)
  - Product search, filtering, and sorting
  - Cart functionality and checkout flow
- Admin Dashboard:
  - Upload, edit, and delete products
  - Manage user permissions
  - Internal tools for catalog and order management
- Backend Functionality:
  - Products are grouped into categories and sections
  - Discounts support
  - Swagger-generated API docs
  - Image upload handling via Multer
 
## Teck Stack

- Frontend:
  - React 18
  - Vite
  - Tailwind CSS
  - React Hook Form
  - Axios, SweetAlert2
- Backend:
  - Express.js
  - MySQL 5.7
  - Knex.js for queries and migrations
  - Swagger for API docs
 
## Limitations & Next Steps
This is a work in progress with several planned improvements:
- Improve responsiveness, especially on the admin dashboard
- Implement email verification and password recovery
- Add product reviews and better error handling
- Improve admin UX
- Write unit tests
Some placeholder content is still visible (e.g., footer, FAQs), and error states are not yet fully handled.

## Deployment & Live

The app was previously deployed on AWS with separate services for the backend (EC2) and frontend (S3). Configuration was adapted to support CORS and MySQL 5.7 compatibility. The deployment was taken down to avoid recurring costs, specially because AWS costs for using legacy versions of MySQL, but the experience informed future planning for cloud-hosted environments.

![Screenshot of the App](https://images.ctfassets.net/5z7iu4f576oy/1LwU8XyTQG0C5hcuCQ05A7/c88e179228008127a790e8000e58d5a2/alleastore.png)



