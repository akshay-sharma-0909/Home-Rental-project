## Home Rental Platform
**Home Rental Platform**is a web-based application designed to connect property owners and users through a centralized rental management system. The platform allows property owners to create, update, and delete rental listings, while users can browse properties and share their experiences through reviews.

As the demand for online rental platforms continues to grow, there is a strong need for a secure and structured system that enables property management and user interaction. This application addresses that need by offering role-based access, listing management, and user-generated reviews to enhance transparency and trust.

## Features
- ** Property Listing Management **: Property owners can create, update, and delete rental property listings.

- **Property Browsing **: Users can browse available rental properties and view detailed listing information.

- ** User Reviews **: Authenticated users can write reviews for properties and delete their own reviews.

- ** User Authentication **: Secure user and owner accounts with role-based access control.- 

## Installation
**Prerequisites**
- Node.js (for backend)
- MongoDB (for database)
- MVC Architecture – Model–View–Controller pattern

**Steps to Install**
1. Clone the Repository:
```bash
git clone https://github.com/akshay-sharma-0909/Home-Rental-project
```
2. Install Backend Dependencies:

Navigate to the Listing/ folder and run:
```bash
npm install
```

3. Install Frontend Dependencies:

Since the frontend uses HTML, CSS, and JavaScript, there are no specific package dependencies. You can simply open the frontend/ folder and start working with the files.

4. Configure Database:

Set up your MongoDB instance and configure the connection string in the backend/config/db.js file.

5. Start the Application:

For the backend:
```bash
cd listing
node app.js
```

6. Visit http://localhost:3000 in your browser to access the application.

## Tech Stack
- Backend: Node.js, Express.js
- Database: MongoDB
- MVC Architecture – Model–View–Controller pattern

## Folder Structure
```
project-root/
│
├── controllers/
│   └── Handles request logic (business logic for routes)
│
├── init/
│   └── Initialization files (DB connection, config setup, seed data, etc.)
│
├── model/
│   └── Database models / schemas (MongoDB/Mongoose models)
│
├── patches/
│   └── Utility patches or fixes (custom overrides / helpers)
│
├── public/
│   └── Static assets (CSS, JS, images)
│
├── routes/
│   └── Express route definitions (API endpoints)
│
├── utils/
│   └── Utility/helper functions (reusable logic)
│
├── views/
│   └── Server-side templates (EJS / Pug / Handlebars)
│
├── .gitignore
│   └── Files/folders ignored by Git
│
├── CloudConfig.js
│   └── Cloud service configuration (e.g., Cloudinary, AWS)
│
├── joi.js
│   └── Joi validation schemas for request validation
│
├── app.js
│   └── Main Express app configuration
│
├── middleware.js
│   └── Custom Express middleware (auth, error handling, etc.)
│
├── package.json
│   └── Project metadata, scripts, dependencies
│
└── package-lock.json
    └── Dependency lock file

```

## Screenshots
***Login page***
![image](https://github.com/user-attachments/assets/3a821b29-d347-4628-a708-522aafe01cbe)


***User Page***
![image](https://github.com/user-attachments/assets/4bf3c3ce-80d3-4627-a287-e302be97b22f)


![image](https://github.com/user-attachments/assets/9a918fd7-14b0-4144-b148-2338344a7c03)

![image](https://github.com/user-attachments/assets/43769c5a-fff8-4544-ba10-fedd9a79d4ca)


***Admin Page***
![image](https://github.com/user-attachments/assets/526920e5-2938-40f6-b0a5-d9d5b59d2e84)

![image](https://github.com/user-attachments/assets/c4b4857b-1ded-486a-93bf-ff14ab7185bf)


## Contributing
We welcome contributions from the community! If you'd like to improve or add features to this project, feel free to fork the repository, make your changes, and submit a pull request. Please ensure that your code adheres to the project's coding standards and is well-documented.




** Node.js and Express.js for building the backend server.

** MongoDB for storing data.
