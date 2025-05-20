Step 1 :
Download the Repository on your Computer and make sure you must have Intellij Idea for Smooth Execution of Spring Boot Application.

Step 2 :
Only Create & Use the MYSQL Database with given name as "ecommerce".

Step 3 :
Open application.properties file and edit the MYSQL Database Creradentials, such as username, password and Database name.
NOTE - "IN THESE REPOSITORY I HAVE USED MY CREDENTIALS, SO KINDLY DO NOT USE MY CREDENTIALS EITHER IT WILL RESULT AS APPLICATION FAILURE".

Step 4 : 
Before Starting the Spring-boot Application you must have to insert the Values in the Tables of Database which you have created.

* * * * * * * * * * * * * * * * * * * * * EXAMPLE/execute the query SAMPLE SQL QUERY are as follows * * * * * * * * * * * * * * * * * * * * *  

create database ecommerce;

use ecommerce;


INSERT INTO user (id, name, email, password) VALUES (1, 'Aashutosh', 'ashuay069@gmail.com', '123');



INSERT INTO product (name, description, price, image_url, category) VALUES
-- 📌 Electronics
('Laptop', 'High-performance laptop for gaming and work', 75000, 'https://cdn.pixabay.com/photo/2020/10/21/18/07/laptop-5673901_1280.jpg', 'Electronics'),
('Apple MacBook', 'Lightweight and powerful MacBook with Retina Display', 95000, 'https://cdn.pixabay.com/photo/2016/11/29/05/08/apple-1867461_1280.jpg', 'Electronics'),
('Headphones', 'Wireless noise-cancelling headphones', 5000, 'https://cdn.pixabay.com/photo/2018/10/04/05/38/headphone-3722950_1280.jpg', 'Electronics'),

-- 📌 Clothing
('Men Shirts', 'Cotton casual shirts for men', 1999, 'https://cdn.pixabay.com/photo/2014/08/26/21/49/shirts-428618_640.jpg', 'Clothing'),
('Women Fashion', 'Trendy women outfits for all seasons', 2499, 'https://cdn.pixabay.com/photo/2017/01/14/10/03/fashion-1979136_640.jpg', 'Clothing'),
('Baby Shoes', 'Soft and comfortable baby shoes', 999, 'https://cdn.pixabay.com/photo/2017/09/13/18/06/babys-bootees-2746390_640.jpg', 'Clothing'),

-- 📌 Gadgets
('Studio Headset', 'High-quality audio headset for music production', 11999, 'https://cdn.pixabay.com/photo/2022/06/21/21/15/audio-7276511_640.jpg', 'Gadgets'),
('Nikon Camera', 'Professional DSLR camera with high-quality lens', 129999, 'https://cdn.pixabay.com/photo/2023/11/14/15/46/nikon-8388022_640.jpg', 'Gadgets'),
('Wireless Earphones', 'Compact and stylish wireless earphones', 3499, 'https://cdn.pixabay.com/photo/2020/09/24/14/51/earphones-5598952_640.jpg', 'Gadgets');

select * from product;


Step 5 :
Test Your API endpoints using Postman Tool.

These Are the Api URL's 

GET = http://localhost:8082/users    #it is get request which return the users details.
GET = http://localhost:8082/products   #it is get request for showing the Product Details as Category wise.

Step 6 :
check for required dependencies such as spring web, spring JPA and Spring Mysql Connector inside pom.xml if it is not there then add the dependency manually.

Step 7 :
First, Run the Spring Boot Project inside the "Ecomm" folder. If application run successfull, then your Backend is Working Properly.

Step 8 :
After Backebnd Application runs Successfull, move to your Frontent part.
The "Ecomm-UI" is Your Front end Folder , So you open these folder in Vs-code IDE, open index.xml and open live server.
Your Application Runs Successfull on web browser


----------------------------------------------------------------------TECHNOLOGY STACK---------------------------------------------------------------------------------


Backend : Spring-boot, Spring Starter Project
Frontend : HTML, Bootstrap, JavaScript
IDE : Intellij ("BACKEND") & VsCode ("FRONTEND")
API Testing Tool : Postman
Database : MySql



