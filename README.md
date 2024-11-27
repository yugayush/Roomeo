# Fullstack Room Booking System Project
Roomeo is a Fullstack Room Booking System is a fully developed and feature-rich application that streamlines room reservation management. It caters to users and administrators, offering a seamless and secure experience for booking rooms, managing profiles, and overseeing administrative tasks. With a robust backend built using Spring Boot and a dynamic frontend developed in React.js, this project is a complete solution for modern room booking needs.

## 🌟 Key Features

- User Functionality
    - Room Search and Results:
        A user-friendly interface to search for available rooms based on preferences.

- Filtered results with pagination for an optimized browsing experience.
    - Room Details:
        Comprehensive room information, including images, descriptions, and pricing.
- Real-time availability status.
    - Booking Management:
        Effortless booking process with a secure checkout flow.
- View, manage, and cancel bookings through a dedicated user portal.
    - User Authentication and Profile:
        Secure login and registration with JWT-based authentication.
- Personal profile management with options to update user details.
    - Guarded Routes:
        Ensures secure access to user-specific pages using authentication guards.
- Admin Functionality
    - Admin Dashboard:
        A centralized panel to manage rooms, bookings, and user data.
- Metrics and insights into the platform's overall performance.
    - Room Management:
        Add, update, or delete room listings.
- Upload and manage room images securely using AWS S3.
    - Booking Oversight:
        View and manage all user bookings, including cancellations and modifications.

## 🛠️ Technology Stack

- Frontend:
    - React.js: For building an interactive and responsive user interface.
    - Redux: Manages the application state for better scalability and maintainability.
    - Tailwind CSS: Ensures a modern and attractive design with utility-first styling.
    - Axios: Handles seamless API communication with the backend.

- Backend:
    - Spring Boot: Provides a robust framework for backend development.
    - Spring Security: Implements user authentication and role-based authorization.
    - Spring Data JPA: Simplifies database operations with a powerful ORM layer.
    - AWS S3: Facilitates secure and scalable storage for media files.

- Database:
    - PostgreSQL: A reliable and feature-rich relational database for storing application data.

- Authentication:
    - JWT (JSON Web Tokens): Ensures secure, stateless authentication and API protection.

## 📚 System Architecture
- Entities and Models:
    - Well-defined entities for users, rooms, and bookings form the backbone of the system.

- Relationships between entities ensure data consistency and integrity.
    - DTOs and Mappers:
        Data Transfer Objects (DTOs) streamline communication between the frontend and backend.
        Mapping utilities convert entity data to DTOs and vice versa.

- Repositories:
    - Custom repository classes handle data operations, ensuring optimized database queries.
        Service Layer:
            Dedicated service classes encapsulate business logic, including user, room, and booking services.
        Security Layer:
            Configurations for CORS, JWT Authentication Filters, and Security Filter Chains.
        Implements granular access controls for users and administrators.
        
- Utility Features:
    - Tools for entity-to-DTO mapping, exception handling, and file storage operations.

## 📄 Frontend Features
- Homepage:
    Welcomes users with an overview of the platform and quick access to room search functionality.

- Dynamic Components:
    - A navbar and footer for seamless navigation across the application.
    - Dedicated components for displaying search results, room details, and user profiles.

- Pages:
    - Room Search and Results: Allows users to find available rooms quickly.
    - Find Booking: Enables users to search for and manage their bookings.
    - Room Details: Displays all information about a selected room.
    - User Profile: Facilitates editing profile information.
    - Login and Registration: Provides secure authentication.
    - Admin Pages: Offers tools to manage rooms and bookings.

## 🔒 Security Features
    - JWT authentication secures API access, ensuring only authorized users can interact with protected endpoints.
    - Authentication guards prevent unauthorized access to sensitive frontend routes.
    - CORS configuration enhances security by controlling cross-origin resource sharing.

