## EV Charging Station Finder and Slot Booking System
**EV Charging Station Finder and Slot Booking System** is a web-based application designed to help electric vehicle (EV) owners easily find nearby charging stations and book slots in advance . This system is aimed at improving the EV charging experience, ensuring convenience, accessibility, and reliability for users while promoting the adoption of electric vehicles by reducing charging anxiety.

As the adoption of electric vehicles continues to rise, the need for a streamlined and efficient way to locate, reserve, and pay for charging slots becomes critical. This application addresses that need by offering a simple yet powerful solution.

## Features
- **Charging Station Locator:** Find nearby EV charging stations using geolocation services.
- **Slot Booking:** View available slots and reserve a time for charging your EV.
- **Real-time Updates:** Live status of charging slots and availability.
- **User Profiles:** Create accounts to manage bookings and transaction history.
- **Station Management:** Admin panel for charging station operators to manage bookings and monitor station performance.

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
