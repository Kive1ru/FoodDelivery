# Food Delivery Project

## Description
This is a food delivery project that allows users to order food from different restaurants and have it delivered to their location. The project has both the user and the admin side. The user side is built on Wechat mini-program (frontend_phone) and the admin side is built on the web (Using Nginx - frontend_web). The user can view the restaurants, the food items, and place an order. The admin can view the orders and change the status of the orders.

## Instructions for frontend_web
please copy the frontend_web folder to the Nginx/html folder. Then, configure the Nginx to listen to the port 80 and change the root to the html/frontend_web folder. Keep the index as index.html. Run the Nginx and open the browser to localhost:80.