# Overview
This file explains this project.
It contains information that is commonly required to understand what this project is about.

# The Happy Store
This project implements a simple clothing store called the Happy Store. The website is a simple e-commerce website that allows admins to create products and classify them into categories. And it allows customers to make orders.

# Table of contents
* [Project Setup](#project-setup)
* [Project Requirements](#project-requirements)
* [Database Schema](#database-schema)
* [Demo](#demo)


## Project Setup

In this section, the key points about technologies used in the project are mentioned, along with how the project can be run.

### Technologies and Dependencies

* Project is created with:
  * Laravel: v9.37.0
  * OS: macOS v12.6
  * Bootstrap: v5.2.2
  * Laravel Breeze: vv1.14.2

### Installing & Executing program

To run this project locally, just download a copy of the code and run the following commands:
```
$ cd happy_store # this is the project folder you downloaded
$ npm install
$ composer install
$ php artisan migrate
$ php artisan serve
```

## Project Requirements
In this section, a list of all the requirements/features of the project are presented.
Put an X between the brackets for each feature that has been developed and tested by you.

### Admin:
- [X] An Admin account should be created by the developer.
- [X] The admin should be able to log into the website.
- [X] The logged-in admin should be able to create, list, update, and delete different product categories and subcategories.
- [ ] The logged-in admin should be able to create, list, update, and delete different products.
- [X] The logged-in admin should be able to add and remove products from subcategories.
- [ ] The logged-in admin should be able to see a list of customer orders.
- [ ] The logged-in admin should be able to view the details of customer orders.
- [X] The logged-in admin should be able to update any order’s status.
- [ ] The logged-in admin should be able to log out of the website.


### Customer:
- [X] The customer should be able to see a list of products on the website.
- [X] The customer should be able to search for products by name.
- [ ] The customer should be able to filter products.
- [ ] The customer should be able to view a specific product’s details.
- [ ] The customer should be able to register an account on the website.
- [X] The customer should be able to log into their account on the website.
- [X] The logged-in customer should be able to add a product to their shopping cart.
- [X] The logged-in customer should be able to view the products added to their cart.
- [ ] The logged-in customer should be able to remove a product that was added to their shopping cart.
- [X] The logged-in customer should be able to complete their order by entering their shipping information and confirming their order.
- [X] The logged-in customer should be able to view a list of their orders and their statuses.
- [ ] The logged-in customer should be able to view the details of their orders.
- [ ] The logged-in customer should be able to log out of the website.

## Database Schema

![schema](https://user-images.githubusercontent.com/30433769/198361261-a91ba575-f3b6-47cf-a406-53015d8b27a9.jpeg)


## Demo 

[https://youtu.be/kwvpfTC8-go](https://youtu.be/kwvpfTC8-go)
