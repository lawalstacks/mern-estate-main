Real Estate Platform - MERN Stack

This is a full-featured real estate application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It allows users to browse, list, and manage real estate properties. The platform includes authentication, property listing management, and property search functionalities, making it an ideal solution for individuals or businesses in the real estate industry.

Features

User Authentication: Secure login and registration with JWT-based authentication.

Property Listings: Users can view, add, edit, and delete property listings with detailed information including images, pricing, location, and description.

Property Search & Filters: Advanced search with filtering options based on property type, price range, location, etc.

Favorites: Registered users can bookmark properties and view them in their favorites list.

Admin Dashboard: Admin users can manage all property listings, users, and site settings.

Interactive Map: Integrates Google Maps to show property locations visually.

Responsive Design: Fully responsive and optimized for mobile devices.


Tech Stack

MongoDB: For database management, storing property listings, user data, and other information.

Express.js: Backend framework for handling API requests and user authentication.

React.js: Frontend framework for building a responsive and dynamic user interface.

Node.js: Server-side runtime to handle backend logic and API communication.


Installation

1. Clone the repository:

git clone https://github.com/username/real-estate-platform.git


2. Install server dependencies:

cd real-estate-platform
npm install


3. Install client dependencies:

cd client
npm install


4. Create a .env file in the root folder and add the following:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=your_cloudinary_url_for_image_uploads


5. Start the development server:

npm run dev


6. Access the app at http://localhost:3000.




