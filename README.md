# Food Ordering Website PHP

A simple and intuitive food ordering website built using **PHP**. This project provides users a streamlined experience for browsing, selecting, and ordering their favorite meals online. It also includes an admin panel to manage menus, orders, and other website functionalities.

## Features

### User Features
- **Browse Menu**: View the complete menu with categories and pricing.
- **Search Functionality**: Quickly find specific dishes.
- **Order Food**: Add items to a cart and place orders.
- **Responsive Design**: Optimized for mobile and desktop devices.

### Admin Features
- **Dashboard**: View and manage orders, menu items, and other statistics.
- **Menu Management**: Add, update, or remove menu items.
- **Order Management**: View and update order statuses.
- **Category Management**: Organize dishes into categories.

## Tech Stack
- **Front-End**: HTML, CSS, JavaScript
- **Back-End**: PHP
- **Database**: MySQL
- **Others**: Bootstrap for UI components

## Installation and Setup

### Prerequisites
- PHP (Version 7.4 or higher)
- MySQL Server
- Apache Server (e.g., XAMPP, WAMP)

### Steps to Run Locally
1. Clone the repository:
    ```bash
    https://github.com/omkeshri/food-ordering-website-php.git
    ```

2. Navigate to the project directory:
   ```bash
   cd food-ordering-website-php
   ````

3. Set up the database:
   - Create a MySQL database.
   - Import the `database.sql` file located in the repository into your database.

4. Configure database connection:
   - Open `config.php` (or similar configuration file).
   - Update the database credentials (host, username , password, database name).

5. Start the server:
   - Use XAMPP or WAMP to start the Apache and MySQL services.
   - Place the project folder in the `htdocs` directory (for XAMPP) or equivalent for your setup.

6. Access the application:
   - Open your browser and go to `http://localhost/food-ordering-website-php`.
  
## Contributing

Feel free to fork this repository and contribute by submitting a pull request. For major changes, please open an issue first to discuss what you want to change.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
