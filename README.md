# JUMPSTART Ecommerce Site

## Project Overview

**Welcome to the JUMPSTART Ecommerce Site! This platform is designed to cater to three types of users: Users, Administrators, and Staff. Each user type has specific functions they can perform within the portal.**

## User

1. **Register in the Portal:** New users can sign up for an account.
2. **Login to the Portal:** Registered users can log in to their accounts.
3. **View and Update Profile:** Users can access and modify their profile information.
4. **Browse Products:** Users can explore the list of available products.
5. **Add to Cart:** Users can add desired products to their shopping cart.
6. **View Products:** Users can view details of products in the catalog.
7. **View Order History:** Users can check their order history.

## Admin

1. **Register in the Portal:** Administrators can create an account on the portal.
2. **Login to the Portal:** Administrators can log in to their accounts.
3. **User and Staff Management:** Administrators can view, edit, and delete user and staff accounts.
4. **Mark as Administrator or Staff:** Administrators have the authority to designate users as administrators or staff members.
5. **View and Update Profile:** Administrators can access and update their own profile information.
6. **Product Management:** Administrators can manage the products available on the portal.
7. **Product Category Management:** Administrators can oversee and modify product categories.
8. **Add Products:** Administrators can add new products to the catalog.

# Staff

1. **Register in the Portal:** Staff members can register on the portal.
2. **Login to the Portal:** Staff members can log in to their accounts.
3. **Product Management:** Staff members have the authority to manage products on the portal.
4. **Product Category Management:** Staff members can oversee and modify product categories.

**The following actions are accessible to all users, including User, Admin, and Staff:**

1. **Visit Home Page:** Navigate to the main landing page of the website.
2. **View Product List:** Browse and explore the available list of products.
3. **Search Products:** Utilize the search functionality to find specific products.
4. **About Us Page:** Access information about the background and purpose of the website.
5. **Contact Us Page:** Connect with the website administrators or support team.
6. **Privacy Policy:** Review the privacy policy governing the use of personal information.
7. **Terms and Conditions:** Familiarize yourself with the terms and conditions regulating the use of the website.

## System Requirements

Java Development Kit (JDK) 8 or later <br>
Spring Tool Suite (STS) for importing and running the project <br>
MySQL database server <br>
Web browser for accessing the application

## How to run
1. **Import Existing Project into STS**
2. **Create MySQL database**

```bash
mysql> create database jumpstart1
```

3. **Setup application.properties**

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/jumpstart1
spring.datasource.username=<YOUR_DB_USERNAME>
spring.datasource.password=<YOUR_DB_PASSWORD>
```
4. **Run Java Application and open [http://localhost:9090](http://localhost:9090)**

5. ## Project Result

#### Landing Page
![image](https://github.com/Nilupulie-Hewagamage/Jumpstart/assets/137420146/6e32e2b9-e539-4610-a438-2903c65736b3)

#### About Us Page
![image](https://github.com/Nilupulie-Hewagamage/Jumpstart/assets/137420146/bd2ddcff-ae69-4472-9e2d-416b2c9d9702)

#### Contact Us Page
![image](https://github.com/Nilupulie-Hewagamage/Jumpstart/assets/137420146/249e7228-03dd-41a6-84b7-87528fd64e80)

#### Product Page
![image](https://github.com/Nilupulie-Hewagamage/Jumpstart/assets/137420146/6f08c1c6-ecd0-4076-82e3-d18163455304)

##### Order Products Page
![image](https://github.com/Nilupulie-Hewagamage/Jumpstart/assets/137420146/b94a5114-af83-4dcb-a961-681c474e1344)

