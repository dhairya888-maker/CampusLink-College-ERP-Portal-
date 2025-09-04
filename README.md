# Campus Link - MERN Stack

A comprehensive, full-stack Enterprise Resource Planning (ERP) system designed for educational institutions. This application, "Campus Link," streamlines academic processes with dedicated, role-based portals for Admins, Faculty, and Students. It is built using the MERN stack and secured with JWT for robust authentication.

## ✨ Features

### Core Features (Common for All Roles)
* **Secure Authentication**: JWT-powered login system to ensure data privacy.
* **Role-Based Access**: Dedicated dashboards and functionalities tailored for Admins, Faculty, and Students.
* **Profile Management**: All users can update their personal details and change their passwords.
* **Modern UI**: Clean, intuitive user interface with built-in form validation and error handling.

### 👨‍💻 Admin
* **User Management**: Add, delete, and view profiles of students, faculty, and other admins.
* **Academic Management**: Create new departments and add subjects to the curriculum.
* **Communication**: Create and broadcast notices to all users.

### 🧑‍🏫 Faculty
* **Attendance Tracking**: Mark and manage student attendance records.
* **Academic Assessment**: Create new tests and upload student marks.
* **Information Access**: View lists of assigned students and subjects.

### 🎓 Student
* **Performance Monitoring**: Check personal attendance records and view test marks.
* **Academic Information**: Access the list of currently enrolled subjects.

## 🛠️ Tech Stack

* **Frontend**: React.js, Redux, Tailwind CSS, Material-UI Icons
* **Backend**: Node.js, Express.js
* **Database**: MongoDB
* **Authentication**: JSON Web Tokens (JWT)

## 🚀 Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

* Node.js and npm installed
* A MongoDB Atlas account and your connection URI

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/campus-link.git](https://github.com/your-username/campus-link.git)
    cd campus-link
    ```

2.  **Setup the Backend Server:**
    ```bash
    # Navigate to the server directory
    cd server

    # Install dependencies
    npm install

    # Create a .env file in the 'server' folder
    # Copy the contents of .env.example into it
    # Replace the MONGODB_URI with your MongoDB Atlas connection string

    # Start the server
    npm run start
    ```

3.  **Setup the Frontend Client:**
    ```bash
    # Open a new terminal and navigate to the client directory
    cd client

    # Install dependencies
    npm install

    # Start the React application
    npm run start
    ```

4.  **Access the Application:**
    * The application should now be running on `http://localhost:3000`.
    * The server will be running on `http://localhost:5000` (or your configured port).

## 🔑 Dummy Admin Credentials

After successfully running the server for the first time, a dummy admin account is automatically created.

* **Login URL**: `http://localhost:3000/login/adminlogin`
* **Username**: `ADMDUMMY`
* **Password**: `123`

## 🔮 Future Enhancements

* **Mobile Responsiveness**: Implement a fully responsive design for seamless access on all devices.
* **Expand Modules**: Add non-academic sections such as library management, hostel management, and accounts.
* **Enhanced Admin Controls**: Provide more granular permissions and freedom to admins while managing users and subjects.
