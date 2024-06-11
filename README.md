# oh-yo 

This project is an end-to-end booking platform developed to allow property owners to list their properties and enable customers to connect with them. The application is built using Node.js, Express.js, MongoDB, and React.js.

# Features:-
-Property listing by owners.
-Customer property search and booking.
-User authentication.
-Secure user data storage.
-Dynamic route handling.

# Technologies Used:-
-Frontend: React.js
-Backend: Node.js, Express.js
-Database: MongoDB

#Project Usage:-

The booking platform is designed to facilitate property rentals by connecting property owners with potential customers. Here are the main uses of the project:-

1.Property Listing: Property owners can register on the platform and list their properties. They can provide details such as property type, location, price, and availability.

2.Property Search and Booking: Customers can browse through the listed properties, search for specific criteria, and book properties that meet their needs.

3.User Authentication: The platform supports user authentication, allowing both property owners and customers to create accounts, log in, and manage their profiles.

4.User Data Management: User data, including property details and booking information, is securely stored and managed within the platform.

#How the Technologies Work:-
1. Frontend: React.js
React.js is a JavaScript library for building user interfaces, particularly single-page applications where the user experience is dynamic and responsive.

1.1 Component-Based Architecture: React breaks the UI into reusable components, making the code modular and easier to manage.
1.2 State Management: React manages the state of the application, ensuring that the UI updates automatically when the state changes.
1.3 API Calls: React makes HTTP requests to the backend to fetch or update data, which is then used to update the UI.

2. Backend: Node.js and Express.js
Node.js is a runtime environment that allows JavaScript to be run on the server side.
Express.js is a web application framework for Node.js, providing a robust set of features to develop web and mobile applications.

2.1.Routing: Express.js handles the routing of HTTP requests. For example, when a user logs in, a POST request is sent to /api/users/login, and Express routes this request to the appropriate controller.
2.2.Middleware: Express.js uses middleware functions to handle requests. Middleware can perform tasks such as logging, authentication, and data validation.

3. Database: MongoDB
MongoDB is a NoSQL database that stores data in JSON-like documents. 

3.1.Data Storage: MongoDB stores user information, property details, and booking data in collections. 
3.2 Schema Design: Using Mongoose  schemas are defined to enforce a structure for the documents in the database.
3.3 Querying: MongoDB allows for efficient querying of data.

#How They Work Together:-
1.User Interaction: The user interacts with the application through the React.js frontend. 

2.API Requests: The React.js frontend makes API requests to the Node.js and Express.js backend to retrieve or modify data. 

3.Data  Storage: The backend processes these requests, performs any necessary validation or business logic, and interacts with the MongoDB database to store  data.

4.Response Handling: The backend sends responses back to the frontend, which updates the user interface accordingly.
