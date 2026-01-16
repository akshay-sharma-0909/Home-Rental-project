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

6. Visit https://alive-project-145d.onrender.com in your browser to access the application.

## Tech Stack
- Backend: Node.js, Express.js
- Database: MongoDB
- MVC Architecture – Model–View–Controller pattern

## Folder Structure
```
project-root/
│
├── controllers/        # Business logic for routes
├── init/               # DB connection & initialization files
├── model/              # MongoDB schemas & models
├── patches/            # Utility patches or fixes
├── public/             # Static assets (CSS, JS, images)
├── routes/             # Express route definitions
├── utils/              # Helper & utility functions
├── views/              # EJS templates
│
├── .gitignore
├── CloudConfig.js      # Cloud service configuration
├── joi.js              # Joi validation schemas
├── app.js              # Express app entry point
├── middleware.js       # Custom middleware
├── package.json
└── package-lock.json

```

## Screenshots
***Login page***
<img width="938" height="321" alt="Image" src="https://github.com/user-attachments/assets/de8f7a34-180e-4637-8a22-9394656ac142" />



***User Page***
<img width="1272" height="611" alt="Image" src="https://github.com/user-attachments/assets/128872d9-ba9f-4423-b554-096c7a439450" />




***Admin Page***
<img width="1146" height="541" alt="Image" src="https://github.com/user-attachments/assets/3c4a869d-700e-4897-a15d-408c2c15e5f7" />
<img width="903" height="821" alt="Image" src="https://github.com/user-attachments/assets/d67156e0-ae9a-4d32-b684-0807015562d2" />




## Contributing
We welcome contributions from the community! If you'd like to improve or add features to this project, feel free to fork the repository, make your changes, and submit a pull request. Please ensure that your code adheres to the project's coding standards and is well-documented.




** Node.js and Express.js for building the backend server.

** MongoDB for storing data.
