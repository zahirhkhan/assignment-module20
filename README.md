# Product Management System

This is a **Product Management System** built with Laravel and Tailwind CSS, offering a comprehensive CRUD (Create, Read, Update, Delete) system for managing products. The system also includes sorting, search capabilities, and image handling for each product.

## Features

- **Add, Edit, Delete Products**: Full CRUD operations to manage products.
- **Search & Filter**: Search products by ID or description, and sort by various attributes.
- **Responsive Design**: Styled with Tailwind CSS to ensure a consistent look across devices.
- **Image Handling**: Upload, preview, and display images for each product.
- **Notifications**: Success messages on product updates and actions using Alpine.js for smooth, temporary notifications.

## Project Setup

Follow the steps below to clone, set up, and run the project on your local development environment.

### Prerequisites

Make sure you have the following installed:

- [PHP](https://www.php.net/downloads) (version 8.0 or higher)
- [Composer](https://getcomposer.org/download/)
- [Node.js & npm](https://nodejs.org/en/download/) (for frontend dependencies)
- A local server environment like [Laravel Herd](https://herd.laravel.com/) or [XAMPP](https://www.apachefriends.org/).

### Installation Instructions

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
    ```
   
2. **Install Composer Dependencies**
    
    ```bash
   composer install
    ```
3.	**Install NPM Dependencies**
    
    ```bash
   npm install
   npm run dev
   ```

4.	**Environment Setup**

•Copy the example environment file and modify it as needed:

  ```bash
   cp .env.example .env
   ```
•Generate an application key:
   
   ```bash
    php artisan key:generate
   ```

5.	**Database Setup**
•Configure your .env file with your database credentials. 
•Run the migrations to set up the database schema:

   ```bash
   php artisan migrate
   ```

6.	**Products can be added manually via the frontend interface.**
•Navigate to the product creation page after starting the application to add your products.

7.	**Storage Link**
Create a symbolic link for the storage folder to access uploaded images:

   ```bash
   php artisan storage:link
   ```

8.	**Run the Development Server**

   ```bash
   php artisan serve
   ```
Visit http://127.0.0.1:8000 in your browser to view the application.

**Usage**

	•	Add New Product: Go to /products/create to add a new product.
	•	Edit & Delete: Use the “Edit” and “Delete” buttons available on the product listing.
	•	Search & Sort: Use the search bar and sorting options to filter and order products.

**Tech Stack**

	•	Backend: Laravel
	•	Frontend: Tailwind CSS, Alpine.js
	•	Database: SQLite or MySQL

**Contributing**

Feel free to submit issues or pull requests. Contributions are welcome!

**License**

This project is open-source and available under the [MIT License].



   

 
    
# assignment-module20
# assignment-module20
