# online_store
# Trendy World Online Store
#Trendy World Online Store is a web-based e-commerce platform that allows users to browse, search, and purchase a wide variety of products online. This project is designed to provide a seamless and user-friendly online shopping experience, both for customers and store administrators. It enables customers to view product details, add items to their cart, and proceed with secure checkout. Store administrators can manage products, track orders, and monitor sales through an intuitive admin panel.
Table of Contents
•	Installation
•	Usage
•	Screenshots
•	Credits
#Installation
1.	Clone the repository:
bashCopy code
git clone https://github.com/Simelweyinkosi1/online_store.git cd online-store 
2.	Install dependencies:
bashCopy code
npm install 
3.	Configure environment variables:
Create a .env file in the root directory and add the following variables:
plaintextCopy code
DATABASE_URL=your_database_connection_string SECRET_KEY=your_secret_key 
4.	Database setup:
Set up your database using the provided schema and seed data scripts.
bashCopy code
npm run db:setup 
5.	Run the application:
bashCopy code
npm start 
6.	Access the application at http://localhost:3000.
Usage
1.	User Registration and Login:
•	Navigate to the registration page to create a new user account.
•	After registering, use your credentials to log in.
2.	Browse and Search:
•	Explore the product categories and use the search bar to find specific items.
•	Click on a product to view its details.
3.	Add to Cart:
•	On the product detail page, click "Add to Cart" to add the item to your cart.
4.	View Cart and Checkout:
•	Click the cart icon to view your cart.
•	Review the items in your cart and click "Proceed to Checkout" to start the checkout process.
5.	Admin Panel:
•	Log in as an admin using the provided admin credentials.
•	Access the admin panel to manage products, orders, and customers.
Screenshots
 Figure 1: Main Logo of the site
![Screenshot_20230625_185458](https://github.com/Simelweyinkosi1/online_store/assets/134647468/244f52c1-04d1-4fa8-837b-2de937833f64)

 
Credits
This project was developed by: Simelweyinkosi Sibindi
•	Simelweyinkosi Sibindi
We would like to acknowledge the contributions of various open-source libraries and frameworks that made this project possible. Special thanks to:
•	Express.js
•	React
•	Node.js
•	PostgreSQL
•	Bootstrap
For any questions or inquiries, please contact us at contact@example.com. Your feedback is highly appreciated!

