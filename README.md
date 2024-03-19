# REST API Ecommerce NestJS challenge

NestJS challenge of a selective process to be made within a week. The system is divided into User, Client, Product, Order, Order Items, and Selling Reports entities containing different types of relationships. Also, the main features are Authentication, Permission, and Clients and Products Management. The API is connected with AWS S3 and deployed on EC2, based on a Clean architecture and documented on Swagger.

## Table of Contents

<ul>
  <li><a href="#getting-started">Getting Started</a></li>
  <li><a href="#installing-and-running">Installing and Running</a></li>
  <li><a href="#features">Features</a></li>
</ul>

---

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need to have Docker, Docker Compose, and Node **version 20.11.1** installed in your machine.

1. Follow the official documentation to install the Node: https://nodejs.org/en/download

### Installing and Running

To run the project for the **first** time you must follow these steps:

1. Clone the GitHub repository:

```bash
git clone https://github.com/Giovaniavs/nestjs-node-challenge.git
```

2. Create a .env file with these credential availeble at: https://github.com/brocoders/nestjs-boilerplate/blob/main/env-example-relational

3. Run the following commands:

3.1 In you .env:
  Change DATABASE_HOST=postgres to DATABASE_HOST=localhost
  Change MAIL_HOST=maildev to MAIL_HOST=localhost

3.2 

```bash
  docker compose up -d postgres adminer maildev
  npm install
  npm run migration:run
  npm run start:dev
```

4. Open http://localhost:3000

## Features


<p align="right">
 Developed by Giovani Albuquerque
</p>