This project is a web application developed as part of the ITI "Web Development using MEARN stack" track.
It allows users to easily book appointments with therapists, securely pay online, and leave ratings and reviews.

Technologies:
React

Node.js

Express

Stripe API

JSON Server

Bootstrap

HTML

CSS

JavaScript

Git & GitHub

To run the project:
1- start the json server:
json-server --watch db.json --port 5000

2- start react:
npm start

3- Start the backend server for Stripe integration:
cd backend
node server.js

Features:
-User Authentication: Securely create an account and log in to access the website.

-Therapist Profiles: View detailed information about therapists, including specialties and experience.

-Appointment Scheduling: Easily book appointments with therapists based on availability.

-Payment Processing: Pay securely online through the website using Stripe.

-Rating and Review: Share experiences by leaving ratings and reviews for visited therapists.

-Search and Filter: Find therapists matching preferences with search and filter options.

-FAQ Section: Access a frequently asked questions section for quick answers.

My part in the project:
-Employing the Stripe fake API in test mode, our payment method ensures a seamless transaction experience. Powered by
Node.js on the backend, pressing the "Book Now" button triggers a redirection to the Stripe checkout form, seamlessly
integrating the payment process.

-The frontend, crafted with React.js, boasts an aesthetically pleasing and responsive design. The booking component,
skillfully implemented with Bootstrap, enhances user interaction and ensures a visually appealing booking journey.

-Post-payment initiation, users are seamlessly directed to either the Payment Successful component or, in the event of a
failure, the Payment Failed component. This thoughtful redirection mechanism ensures clarity and user-friendly feedback
throughout the payment process.
