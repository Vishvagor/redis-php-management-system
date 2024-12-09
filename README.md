# Redis-PHP Management System

This project implements a Department and Employee Management System using **Redis** as the backend data store and **PHP** for server-side scripting. The system is designed to be fast, scalable, and easy to deploy using **Docker**.

## Table of Contents

- [Abstract](#abstract)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [File Structure](#file-structure)
- [Acknowledgments](#acknowledgments)

## Abstract

This project demonstrates the integration of **Redis** with **PHP** for the creation of a scalable, in-memory, real-time data management system for handling department and employee data. The system facilitates features such as browsing departments, viewing detailed employee information, and managing department locations and projects. Using Redis as the database solution enables high-speed data retrieval and improves performance when accessing large amounts of structured data.

## Technologies Used

- **Redis** - In-memory NoSQL database for fast data access.
- **PHP** - Server-side scripting language used to handle the web interface.
- **Docker** - Containerization technology used to isolate services.
- **Python** - Data migration from MySQL to Redis using custom Python scripts.
- **HTML, CSS** - Frontend technologies for creating a responsive UI.

## Setup and Installation

Follow these steps to set up the project locally:

1. Clone the repository to your local machine:

    ```bash
    git clone https://github.com/your-username/redis-php-management-system.git
    ```

2. Navigate to the project directory:

    ```bash
    cd redis-php-management-system
    ```

3. Build and start the Docker containers:

    ```bash
    docker-compose up --build
    ```

4. Open your browser and navigate to: [http://localhost:8081](http://localhost:8081)

## File Structure

```plaintext
redis-php-management-system/
├── src/
│   ├── index.php
│   ├── p1.php
│   ├── deptView.php
│   ├── companyBrowse.php
├── mysql_to_redis.py
├── docker-compose.yml
└── README.md
