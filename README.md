Deliveroo is a courier service application that helps users deliver parcels to different destinations. It provides courier services and offers various features to streamline the parcel delivery process.

   FEATURES
User authentication: Users can sign up, log in, and manage their accounts securely.
Parcel_Order management: Create, view, update, and cancel orders.
Status management: Admin can change the status and present location of a parcel delivery order.
Maps Integration: Display a Google Map with markers showing the pickup location and the destination.Display a Google Map with a line connecting both markers (pickup location and the destination).Display computed travel distance and journey duration between the pickup location and the destination.
Token-based authentication: Secure routes using JWT tokens.


   SETUP
To get started with this project, follow the setup instructions below ;

Clone the repository 
Install dependencies
For frontend (React) cd client npm install
For backend(Python) pipenv install
Running the Application
Start the backend server
Activate the virtual environment if you haven't already: pipenv shell
Start the Flask server: flask run
Start the frontend development server:
Navigate to the frontend directory if you're not already there: cd client
Start the development server:
   User Interaction
Users can interact with the frontend React application by signing up, logging in, creating, managing, and tracking parcel delivery orders.
Admins can interact with the backend Python application to monitor and update parcel delivery statuses and locations.
Usage
   User Authentication
Register: Create a new account by providing a username, email, and password.
Login: Log in with your username and password.
Logout: Log out of your account.
  Parcel_Order Management
Create a parcel delivery order.
Change the destination of a parcel delivery order.
Cancel a parcel delivery order.
See the details of a delivery order.
Track parcel delivery orders.
   Status Management
Admin can change the status and present location of a parcel delivery order.
   Licence
This project is licensed under the MIT License.
