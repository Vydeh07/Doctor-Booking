Doctor Booking Platform
A web-based platform that allows users to log in and book appointments with doctors from different specialties such as dermatologists, general physicians, and more. The platform also includes a doctor portal where doctors can manage appointments and see payment statuses, and an admin portal to monitor patient statistics and payment histories.

Features
User Portal:
User Login/Registration: Users can log in to their accounts and book appointments with doctors.

Specialty-based Doctor Access: Users can select from a variety of doctors based on their specialty (e.g., Dermatologist, General Physician).

Appointment Booking: Users can book appointments and check their appointment status.

Doctor Portal:
Appointment Management: Doctors can view the list of patients who have made appointments.

Payment Tracking: Doctors can see who has paid for their appointments and manage payment status.

Admin Portal:
Patient & Appointment Statistics: Admin can view the total number of patients and the number of appointments made.

Payment History: Admin can view and manage the payment history for appointments.

Technologies Used
Frontend: React, Redux, HTML5, CSS3

Backend: Node.js, Express

Database: MongoDB

Authentication: JWT (JSON Web Tokens)

Other Libraries: Mongoose, Axios, etc.

Setup and Installation
To run this project locally:

1. Clone the repository:
bash
Copy
Edit
git clone https://github.com/Vydeh07/Doctor-Booking.git
2. Navigate to the project directory:
bash
Copy
Edit
cd Doctor-Booking
3. Install dependencies:
For both frontend and backend:

bash
Copy
Edit
npm install
4. Set up environment variables:
Create a .env file in the root directory and define the necessary variables:

plaintext
Copy
Edit
DB_URI=your_mongo_db_connection_string
JWT_SECRET=your_jwt_secret_key
PORT=5000
5. Run the development server:
For the backend:

bash
Copy
Edit
npm run server
For the frontend:

bash
Copy
Edit
npm run client
Visit the platform at http://localhost:3000 in your browser.

Contributing
Fork the repository.

Create a new branch: git checkout -b feature-branch.

Make your changes and commit: git commit -m "Add feature".

Push to the branch: git push origin feature-branch.

Open a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

