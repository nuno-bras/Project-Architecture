# Project Overview: Quarkus with Kotlin Backend Structure Exploration
## 1.Introduction

Welcome to the Quarkus with Kotlin Backend Structure Exploration project! 
This repository is dedicated to exploring and showcasing various ways to 
structure a backend project using the Quarkus framework with Kotlin. Whether 
you are a seasoned developer looking for new insights or someone just starting, 
this project provides a hands-on experience with different project structures.

## 2. Required Tools

The only tool you need to run this project is Docker. If you don't have Docker 
installed on your machine, you can download it from Docker's official website.

The build is executed inside the docker image buildup. You don't need java, nor
kotin installed in your system

## 3. Running the Project

1. To run the project, follow these steps:
2. Ensure you have Docker installed on your machine.
3. Clone this repository to your local machine.
4. Open a terminal and navigate to the project's root directory. 
5. Run the following command to start the project:
```bash
docker-compose up
```

This command will initialize the necessary containers and set up the project
environment.

## 3. Project Context: E-Shop

This project revolves around the development of an e-shop, featuring essential components such as products, shopping lists, orders, and user management. Here's a brief overview of each key element:

- **Products**: Representing the items available for purchase within the e-shop.

- **Shopping Lists**: Allowing users, specifically customers, to create and manage lists of products they intend to purchase.

- **Orders**: The process of completing a purchase, with the execution of orders facilitated through the Stripe payment gateway.

- **Users**: The project includes two types of users:
    - **Customer**: Individuals who browse products, create shopping lists, and place orders.
    - **Owner**: Admin-level users responsible for managing products, orders, and overall e-shop functionality.
