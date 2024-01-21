markdown
# Inventory System

## Overview

This repository contains the source code and database design for an inventory system. The system is designed to manage products, suppliers, orders, and purchases.

## Table of Contents

- [Database Structure](#database-structure)
- [Setup](#setup)
- [Usage](#usage)
- [Sample Data](#sample-data)
- [Contributing](#contributing)
- [License](#license)

## Database Structure

The database consists of the following tables:

- **Supplier:** Stores information about product suppliers.
- **Product:** Represents the products available in the inventory and their associated suppliers.
- **Orders:** Tracks customer orders with details such as order date, product, and quantity.
- **Purchases:** Records product purchases with information on the purchase date, product, and quantity.

## Setup

To set up the inventory system locally, follow these steps:

1. Create a MySQL database and execute the SQL script in `database.sql` to create the necessary tables.
2. 
3. Configure the database connection in the application code.

## Usage

Describe how to use the inventory system, including any command-line instructions or API endpoints.

## Sample Data

Dummy data has been provided in the `database.sql` file to demonstrate the functionality of the system. Use this data for testing and understanding the system's features.
