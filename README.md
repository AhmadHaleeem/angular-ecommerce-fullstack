# angular-ecommerce-fullstack
This is a full-stack e-commerce application built with Angular and Spring Boot. It includes an admin panel for managing products, orders, and users, with Ngrx Store for state management on the frontend, and MySQL as the backend database. The project demonstrates a fully functional, scalable solution for online retail.

Here's your organized README content:

---

# Angular E-Commerce Full Stack Project with Admin Panel

## Overview

This project is a full-stack e-commerce application built using Angular on the frontend and Spring Boot for the backend API. It includes a comprehensive Admin Panel for managing products, orders, and users, and is integrated with MySQL for data storage. The application leverages Ngrx Store for state management, ensuring an efficient and scalable frontend architecture.

## Features

### Customer Features:
- Browse and search products by categories.
- View product details, add to cart, and place orders.
- Manage user profile and view order history.

### Admin Features:
- Manage products: Add, edit, delete products.
- View and manage orders and customers.
- Dashboard with analytics on sales and user activity.

## Technologies Used

### Frontend:
- Angular
- Ngrx Store for state management
- Angular Material for UI components

### Backend:
- Spring Boot for REST API development
- MySQL for database

### Other:
- JWT Authentication
- Responsive design with Bootstrap

## Installation & Setup

### Frontend

1. Clone the repository.
    ```bash
    git clone https://github.com/AhmadHaleeem/angular-ecommerce-fullstack.git
    cd angular-ecommerce-fullstack
    ```
2. Install Angular dependencies.
    ```bash
    npm install
    ```
3. Run the Angular application.
    ```bash
    ng serve
    ```

### Backend

1. Navigate to the backend folder.
    ```bash
    cd backend
    ```
2. Install Java dependencies via Maven.
    ```bash
    mvn install
    ```
3. Start the Spring Boot application.
    ```bash
    mvn spring-boot:run
    ```

### Database Setup

1. Ensure MySQL is installed and running.
2. Create a MySQL database.
    ```sql
    CREATE DATABASE ecommerce;
    ```
3. Update the `application.properties` file with your MySQL credentials.

## Ngrx Store

Ngrx Store is used for handling complex state management in this project, making the application scalable and maintaining a predictable state across various components.

## Contributing

Feel free to submit issues and pull requests to improve the project. Contributions are welcome!

## License

This project is licensed under the MIT License.

---

Feel free to copy this into your README file! If you need any more adjustments, just let me know. 😊