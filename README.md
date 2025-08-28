# MediQuick

MediQuick is an online medicine ordering system developed in Java following the MVC (Model-View-Controller) architecture. It uses MySQL as the backend database, providing a robust solution for pharmacies and customers to manage and order medicines efficiently.

## Features

- User registration and authentication
- Browsing and searching medicines
- Placing and tracking orders
- Admin panel for managing medicines and orders
- Secure database integration with MySQL

## Tech Stack

- **Backend:** Java
- **Architecture:** MVC (Model-View-Controller)
- **Database:** MySQL

## Project Structure

```
mediquick/
│
├── application/          # Main Java application source code (MVC structure)
├── README.md             # Project documentation
```

## Prerequisites

- Java JDK 8 or higher
- MySQL Server
- IDE such as IntelliJ IDEA or Eclipse

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/RashmiFernando/mediquick.git
   cd mediquick
   ```

2. **Set up the MySQL database:**
   - Create a new database in MySQL (e.g., `mediquick_db`).
   - Import any provided `.sql` files or create tables as needed.

3. **Configure database connection:**
   - Update the database credentials (username, password, database name) in the application's configuration file (usually within the `application/` directory).

4. **Build and run the application:**
   - Open the project in your IDE.
   - Build the project and run the main class.

