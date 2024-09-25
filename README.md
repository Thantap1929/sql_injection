# SQL Injection Vulnerability Practice Lab

This project is designed as a practice lab for understanding and experimenting with SQL Injection vulnerabilities. It provides a vulnerable web application built with the intention of demonstrating how SQL Injection attacks work in a controlled environment.

## Features
- A simple web application that includes user and employee information in a single table.
- Purposefully vulnerable to SQL Injection attacks for learning purposes.
- Easy setup using Docker for quick deployment on localhost.
- Includes multiple SQL Injection points to experiment with different types of SQL Injection techniques such as:
  - **In-band SQL Injection**
  - **Blind SQL Injection**
  - **Union-based SQL Injection**

## Getting Started

### Prerequisites
- Docker installed on your system.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Thantap1929/sql_injection.git
2. **Build and run the application using Docker**:
   ```bash
   docker-compose up -d --build
3. **Access the application at http://localhost:8080**:

## Usage
This lab is intended for security professionals, students, and enthusiasts to learn how SQL Injection works and practice different attack techniques. You can test various SQL Injection methods, including:
- Retrieving data using union-based injection.
- Manipulating query logic with in-band SQL Injection.
- Extracting data via blind SQL Injection techniques.
  
## Important Notes
- This project is for educational purposes only. Do not use these techniques on systems without permission.
- The web application contains deliberate vulnerabilities and should never be deployed in a production environment.

