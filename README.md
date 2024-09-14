Clinic Management System :- 

A comprehensive web application designed to automate the administrative and clinical processes of small clinics. This system enables clinic staff and doctors to manage appointments, medical records, prescriptions, billing, and patient records efficiently, minimizing manual errors and improving overall operational efficiency. It also provides patients with the ability to book appointments online and access their medical history securely.

Features
  Appointment Scheduling:   Seamlessly schedule appointments and view available slots.
  Patient Management:       Manage patient information, medical records, and medical history.
  Prescription Management:  Create, update, and print prescriptions for patients.
  Medical Test Records:     Upload and manage lab test reports and records using Cloudinary for cloud storage.
  Billing System:           Generate invoices for patient consultations, tests, and other clinic services.
  User Authentication:      Role-based access for clinic staff and patients using secure authentication.
  Responsive Design:        Mobile-friendly UI for ease of access.


Tech Stack

  Frontend: HTML, CSS, JavaScript
  Backend: Node.js, Express.js
  Database: MongoDB (NoSQL)
  File Storage: Cloudinary (for image and document uploads)
  Version Control: Git and GitHub

Live link - https://medicare-frontend-eight.vercel.app/Landingpage/index.html


Prerequisites :- 

  Node.js (v14 or above)
  MongoDB (Install locally or use a MongoDB cloud instance)
  Cloudinary Account for media storage


Steps to Set Up on Local System :-

Clone the Repository


  git clone https://github.com/vivekpal2001/MedecorHealthHack.git
  cd clinic-management
  Install Dependencies

Ensure you are in the project root directory, then install the required Node.js packages:


  npm install
  Set Up Environment Variables

Create a .env file in the project root and add the following environment variables:


  PORT=3000
  MONGODB_URI=<your-mongodb-uri>
  CLOUDINARY_CLOUD_NAME=<your-cloudinary-cloud-name>
  CLOUDINARY_API_KEY=<your-cloudinary-api-key>
  CLOUDINARY_API_SECRET=<your-cloudinary-api-secret>
  Start MongoDB (if running locally)

If you're using a local instance of MongoDB, ensure it is running:


  mongod
  
  Run the Application

Start the application in development mode:


  npm start
  The server will run on http://localhost:3000.

Access the Application :-

  Open a browser and navigate to:
  
  http://localhost:3000

Database Setup :-

  When you first run the app, it will automatically connect to MongoDB and create the required collections. Ensure that your MongoDB URI in the .env file points to either a local or cloud MongoDB instance.

Key Modules
  Express: Server-side framework for building RESTful APIs and handling routes.
  Mongoose: ODM (Object Data Modeling) library to interact with MongoDB.
  Cloudinary: Cloud storage for media files, integrated for uploading medical records and test results.
  bcryptjs: Password hashing for user authentication.
