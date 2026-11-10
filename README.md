# FSD_2
🏫 Smart Campus Lost and Found System

📌 About the Project

The Smart Campus Lost and Found System is a web-based application developed to help students and staff report, search for, and recover lost belongings within a college campus.

The application provides a centralized platform where users can report lost or found items, upload item images, search for belongings, and identify potentially matching items. It reduces manual effort, saves time, and improves communication between students and staff.

🎯 Objectives

- To provide a centralized platform for lost and found items.
- To make reporting and searching for belongings easier.
- To help users recover their lost items quickly.
- To reduce manual work and improve communication.
- To provide secure user authentication and item management.
- To identify potentially matching lost and found reports.

✨ Features

👤 User Features

- User Registration and Login.
- Browse lost and found items.
- Report lost items.
- Report found items.
- Upload item images.
- Search items by name and keywords.
- Filter items by category and location.
- View matching item suggestions.
- Track reported items through My Activity.
- Private inquiries and contact functionality.

🛡️ Admin Features

- Admin Dashboard.
- Manage reported posts.
- Review item claims.
- Manage registered users.
- Monitor lost and found reports.
- Support item resolution.

🔍 Automatic Item Matching

The system compares lost and found reports using:

- Item Category
- Item Name
- Colour
- Location
- Description Similarity

It generates potential matches to help users identify their belongings.

🛠️ Technologies Used

Technology| Purpose
React.js| Frontend Development
HTML| Web Page Structure
CSS / Tailwind CSS| Styling
JavaScript| Application Logic
Node.js| Backend Runtime
Express.js| Backend Framework
MongoDB| Database
Mongoose| Database Connectivity
JWT| User Authentication
bcrypt| Password Hashing

🏗️ System Architecture

The application follows a Three-Tier Architecture.

1. Presentation Layer: React.js provides the user interface.
2. Application Logic Layer: Node.js and Express.js handle requests and application logic.
3. Database Layer: MongoDB stores user accounts, item reports, and related information.

⚙️ Installation and Setup

Prerequisites

- Node.js
- npm
- MongoDB
- Visual Studio Code
- Web Browser

Step 1: Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

Step 2: Navigate to the Project Folder

cd YOUR_PROJECT_FOLDER

Step 3: Install Backend Dependencies

Navigate to the server folder:

cd server
npm install

Step 4: Configure Environment Variables

Create a ".env" file inside the server folder.

PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/campus_lost_found
JWT_SECRET=your_secret_key

Replace the secret with a secure value.

Step 5: Start the Backend Server

npm start

Step 6: Install Frontend Dependencies

Open another terminal and navigate to the client folder:

cd client
npm install

Step 7: Start the Frontend

npm run dev

Open the local URL displayed in the terminal to access the application.

Note: The folder names and npm scripts above are a standard setup template. Adjust them according to your actual project structure and package.json files.

📸 Application Screenshots

The application includes the following screens:

1. Login Page
2. Browse Lost and Found Items
3. Report an Item Page
4. My Activity Dashboard
5. Admin Dashboard
6. Claims Review
7. Posts Management
8. User Management
9. Lost Items Filter
10. Found Items Filter

🌍 Sustainable Development Goals (SDGs)

This project supports the following United Nations Sustainable Development Goals:

- SDG 12 – Responsible Consumption and Production: Encourages recovery and reuse of belongings and reduces unnecessary replacement.
- SDG 9 – Industry, Innovation and Infrastructure: Promotes digital innovation through a web-based management platform.
- SDG 11 – Sustainable Cities and Communities: Supports an organized and responsible campus community.

🔮 Future Enhancements

- Machine Learning-based image similarity.
- Email and SMS notifications.
- Mobile application support.
- Improved reporting and analytics.
- Additional privacy and verification features.

👩‍💻 Developer

Name: Padala Kavya
Roll Number: 24761A0536
Department: Computer Science and Engineering
College: Lakireddy Balireddy College of Engineering

📄 Conclusion

The Smart Campus Lost and Found System provides an efficient digital solution for managing lost and found belongings within a college campus. It simplifies item reporting, searching, matching, and recovery through a centralized platform. The project demonstrates the practical use of full-stack web development technologies to solve a real-world problem.

---

⭐ If you find this project useful, feel free to explore and contribute!
