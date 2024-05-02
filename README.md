# Software Hubss

![Screenshot (548)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/b869fa21-3721-41bd-9493-2a0a46e63420)


Functionality of the Ecommerce Platform:
1. User Authentication:
 Registration: Users can create accounts by providing necessary details. 
 Login: Authenticated access using username and password. 
 Redirect to the login page for incorrect credentials. 
 Redirect to the home page upon successful login.


![Screenshot (547)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/47e54651-afe8-4eef-bd43-deb4cb721c5b)


3. Profile Management:
 View/Edit Profile: Users can view and update their personal information. 
 Registered Details: Display details provided during registration.


![Screenshot (549)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/8c64c673-9693-4d88-a9fa-b3afda4cc3ca)


4. Product Interaction:
 Product Browsing: Users can explore products categorized and 
 displayed on the platform. 
 Add to Cart: Users can add desired products to their shopping cart. 
 Cart Management: Users can view, update, and remove items from their cart.


![Screenshot (505)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/fd7a51da-2d6f-4d9f-b22c-097f80bb325d)


5. Checkout Process:
 Shipping Details: Users provide shipping information such as address and contact. 
 Payment Options: Secure payment gateway integration for various payment methods. 
 Order Confirmation: Confirmation message with a unique order ID upon successful purchase.



![Screenshot (553)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/20a387c7-df86-49a5-bda4-967694a698c8)




6. Order Management:
 Order Tracking: Users can monitor the status of their orders (processing, shipped, delivered). 
 Invoice Download: Users can download invoices for their orders.

7. Feedback Submission:
 Product Feedback: Users can leave feedback and ratings for products purchased. 
 Feedback Storage: Feedback data is stored securely in the database.


![Screenshot (550)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/0dbf74ed-deaf-43e9-8016-5158819d63c6)



9. Admin Portal Functionality:
 Product Management: Admins can add, edit, or delete products. 
 User Management: Admins can view user profiles and perform actions such as editing or 
deactivating accounts. 
 Feedback Management: Admins can view and respond to user feedback. 
 Order Management: Admins can track orders and update their status.


![Screenshot (552)](https://github.com/shrivaspatkhushbu/Ecommerce/assets/156420014/5d41ac06-3e46-46b4-9bb1-e2721368bc80)


11. Database Management:
 Data Storage: Utilize SQLite database to store user information, product details, orders, and 
feedback. 
 Data Encryption: Implement encryption techniques to safeguard sensitive data.  
12. Scalability and Future Expansion:
 Design for Scalability: Architecture built to handle increasing user and product loads.
 Future Enhancements: Consider adding features based on user feedback and market demands

To run the Program Enter Following Cmd in terminal:
python manage.py makemigrations
python manage.py migrate
python manage.py runserver


