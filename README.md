# CLI Management System

## Project Overview

This is a Command Line Interface (CLI) based Management System built using Python.
The system allows Admins, Managers, and Employees to perform different operations such as managing employees and handling requests.

## Features

* User Authentication
* Admin Dashboard
* Manager Request Handling
* Employee Management
* Email and Password Validation
* Password Hashing for security
* Database Connection Pooling

## Tech Stack

* Python
* MySQL
* CLI Interface
* Layered Architecture

## Project Structure

```
cli/            # CLI menus
services/       # Business logic
repositories/   # Database queries
utils/          # Utility functions
validation/     # Input validation
db_pool/        # Database connection
```

## How to Run

1. Clone the repository

```
git clone https://github.com/eshwarsai2101/managementSystem
```

2. Install dependencies

```
pip install -r requirements.txt
```

3. Run the project

```
python main.py
```
