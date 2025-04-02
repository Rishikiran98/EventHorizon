EventHorizon
EventHorizon is a comprehensive movie ticket booking platform designed to provide users with a seamless experience in discovering, selecting, and reserving seats for their favorite films. This web application integrates dynamic front-end interfaces with robust back-end functionalities to ensure real-time updates and secure transactions.

Table of Contents
Overview

Features

Technologies Used

Installation

Usage

Project Structure

Contributing

License

Overview
In the digital age, the convenience of booking movie tickets online has become a standard expectation. EventHorizon addresses this need by offering a user-friendly platform where movie enthusiasts can effortlessly browse current and upcoming films, view showtimes, select preferred seats, and purchase tickets—all from the comfort of their devices. The system also caters to theater administrators, providing tools to manage movie listings, schedules, and bookings effectively.

Features
User Authentication: Secure registration and login system for users and administrators.

Movie Exploration: Browse and search functionalities to discover movies by genre, rating, or release date.

Showtime Management: Detailed schedules for multiple theaters and screens.

Seat Selection: Interactive seating charts for users to choose their preferred seats.

Booking System: Real-time booking with instant confirmation and e-ticket generation.

Admin Dashboard: Tools for administrators to add or update movie details, manage showtimes, and monitor bookings.

Responsive Design: Optimized for various devices, ensuring a consistent experience across desktops, tablets, and smartphones.

Technologies Used
Front-End:

HTML5 & CSS3: Structure and styling of the web pages.

JavaScript (ES6+): Interactive elements and dynamic content rendering.

React.js: Component-based architecture for building the user interface.

Back-End:

Node.js with Express.js: Server-side logic and API development.

MongoDB: NoSQL database for storing user information, movie details, and booking records.

Mongoose: ODM (Object Data Modeling) library for MongoDB and Node.js.

Additional Tools:

Redux: State management for React components.

JWT (JSON Web Tokens): Authentication and authorization mechanism.

Stripe API: Payment gateway integration for processing transactions.

Installation
To set up the EventHorizon project locally, follow these steps:

Clone the Repository:

bash
Copy
Edit
git clone https://github.com/Rishikiran98/EventHorizon.git
Navigate to the Project Directory:

bash
Copy
Edit
cd EventHorizon
Install Dependencies:

For the Back-End:

bash
Copy
Edit
cd BackEnd
npm install
For the Front-End:

bash
Copy
Edit
cd ../FrontEnd
npm install
Set Up Environment Variables:

Create a .env file in the BackEnd directory with the following variables:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
STRIPE_SECRET_KEY=your_stripe_secret_key
Replace your_mongodb_connection_string, your_jwt_secret, and your_stripe_secret_key with your actual MongoDB URI, JWT secret, and Stripe secret key, respectively.

Start the Development Servers:

Back-End Server:

bash
Copy
Edit
cd BackEnd
npm start
Front-End Server:

bash
Copy
Edit
cd ../FrontEnd
npm start
The application will be running at http://localhost:3000.

Usage
User Registration and Login:

Navigate to the homepage.

Register a new account or log in with existing credentials.

Browse Movies:

Explore the list of currently showing and upcoming movies.

Use the search bar to find specific titles or filter by genre.

View Showtimes and Select Seats:

Click on a movie to view available showtimes.

Choose a preferred showtime and select seats from the interactive seating chart.

Book Tickets:

Proceed to checkout.

Enter payment details and confirm the booking.

Receive an e-ticket via email or download it directly from the website.

Admin Functions:

Log in with admin credentials.

Access the admin dashboard to add new movies, update existing listings, manage showtimes, and monitor bookings.

Fork the Repository:

Click the "Fork" button at the top right of the repository page.

Clone Your Fork:

bash
Copy
Edit
git clone https://github.com/your-username/EventHorizon.git
Create a New Branch:

bash
Copy
Edit
git checkout -b feature/your-feature-name
Make Your Changes:

Implement your feature or fix the identified issue.

Ensure your code follows the project's coding standards.

Commit Your Changes:

bash
Copy
Edit
git commit -m "Add feature: your feature name"
Push to Your Fork:

bash
Copy
Edit
git push origin feature/your-feature-name
Submit a Pull Request:

Navigate to the original repository.

Click on "Pull Requests" and then "New Pull Request."
