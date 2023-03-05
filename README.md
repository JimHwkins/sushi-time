## Developed By:
Corey Silver\
Alex Ferru\
Joseph Du

## Description
Sushi Time is a full-stack online food ordering application that our team developed as a group project. Our application allows users to easily place an order with their favorite restaurant, and once the order is received, the user receives SMS notifications when the order is placed and when the order is ready to be picked up.

As a team, we utilized a variety of technologies, including jQuery, Bootstrap, HTML, CSS, Node, Express, PostgreSQL, and the Twilio API to build this project. We collaborated on designing the user interface and implementing the back-end functionality, which allowed us to gain valuable experience in developing a full-stack web application.

One of the most exciting features of this project was integrating the Twilio API to send SMS notifications to the user. We worked together to ensure that this feature was implemented seamlessly, allowing the user to receive real-time updates about their order status.

Overall, Sushi Time was a challenging and rewarding group project that allowed us to showcase our skills in web development and create a useful application that enhances the user experience.

## Technologies
Front-End: Jquery, Bootstrap, HTML, CSS\
Back-End: Node, Express, PostgreSQL, Twillio API

## Screenshots
Screenshot of the landing page

![Picture of Main Page](https://github.com/corey237/sushi-time/blob/master/screenshots/Main_page.jpeg?raw=true "Main Page")


Screenshot of the Menu Page

![Picture of Menu Page](https://github.com/corey237/sushi-time/blob/master/screenshots/Menu_page.jpeg?raw=true "Menu Page")

Picture of the Checkout Page

![Picture of Checkout Page](https://github.com/corey237/sushi-time/blob/master/screenshots/Checkout_page.png?raw=true "Checkout Page")

Picture of the Order History Page

![Picture of Orders Page Page](https://github.com/corey237/sushi-time/blob/master/screenshots/User_orders_page.png?raw=true "Orders Page")

Picture Showing Mobile View/Responsive Design

![Picture of Admin Order Histry Page](https://github.com/corey237/sushi-time/blob/master/screenshots/Admin_orders_page.png?raw=true "Order History Page (Admin View)")

SMS Notifications User Will Receive After Placing Order

![Picture of Admin Order Histry Page](https://github.com/corey237/sushi-time/blob/master/screenshots/Twilio_sms.jpg?raw=true "SMS Notifications")


## Instructions
1. Create a copy of the .env.example file and rename it to .env
2. Insert the Twilio Authentication Token and SID into the necessary fields within the .env file (Update database information as well if necessary).
3. in your terminal, run <code>npm install</code> to install the dependencies
4. Fix to binaries for sass: <code>npm rebuild node-sass</code>
5. Reset database: <code>npm run db:reset</code>
6. Within the PostgreSQL REPL, Run all of the db/schema files in the correct order e.g. <code>\i 01_users.sql</code>
7.  Go to the db/seeds folder and within the PostgreSQL REPL, run the seeds file for the items table <code>\i 03_items.sql</code>
8. Run the server: <code>npm run local</code>
9. Visit http://localhost:8080/ and create an account to start using the app!

*Note: nodemon is used, so you should not have to restart your server

## Dependencies
* bcryptjs: 2.4.3
* chalk: 2.4.2
* cookie-session: 2.0.0
* crypto: 1.0.1
* dotenv: 2.0.0
* ejs: 2.6.2
* express: 4.17.1
* morgan: 1.9.1
* pg: 8.5.0
* sass: 1.35.1
* twilio: 4.7.2
* uuid: 9.0.0
## Dev Dependencies
* Nodemon: 2.0.10



