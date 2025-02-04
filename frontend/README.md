# Employee Management System

## Overview

The **EMS** is a full-stack web application designed to streamline HR operations. Built with the MERN stack and utilizing Vite for the React frontend, this project offers fast development and a modern development experience. The application supports the following key features:
- **Employee Data Management:** Create, read, update, and delete employee profiles.
- **Attendance Tracking:** Mark daily attendance with check-in/check-out functionality.
- **Leave Management:** Submit and manage leave requests with an approval workflow.
- **Performance Reviews:** Record and view performance evaluations.
- **Role-Based Access Control:** Separate functionalities for HR managers, team leads, and employees.

## Features

- **User Authentication & Authorization:** Secure login and registration with role management.
- **Employee CRUD Operations:** Efficiently manage employee details and records.
- **Attendance Module:** Record and view daily attendance, including timestamps and working hours.
- **Leave Module:** Request, approve, or decline leave applications.
- **Performance Evaluation:** Submit and review performance metrics and feedback.
- **Responsive UI:** Built with React and styled using modern UI libraries for a seamless user experience.
- **Fast Development:** Utilizes Vite for rapid frontend development and hot module replacement.

## Technologies Used

- **Frontend:**
  - React (powered by Vite)
  - Vite (development server and build tool)
  - React Router (for navigation)
  - Tailwind CSS
  
- **Backend:**
  - Node.js & Express.js
  - MongoDB (with Mongoose for data modeling)
  - JWT (for secure authentication)
  
- **Tools & Deployment:**
  - Git for version control
  - Netlify / Vercel for frontend deployment

## Installation

### **Backend Setup**

1. Clone the repository and navigate to the `backend` folder:
    ```bash
    git clone https://github.com/your-username/EMS.git
    cd EMS/backend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the backend folder with the following variables:
    ```env
    PORT=5000
    MONGODB_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret_key
    ```

4. Start the backend server:
    ```bash
    npm run dev
    ```
    The server should start on `http://localhost:5000`.

### **Frontend Setup**

1. Navigate to the `frontend` folder:
    ```bash
    cd ../frontend
    ```

2. Install the dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the frontend folder (if required for environment variables, such as API endpoints).

4. Start the development server:
    ```bash
    npm run dev
    ```
    Vite will serve the frontend on `http://localhost:3000` (or the port specified).

## Usage

- **Registration/Login:** Access the authentication pages to register as a new user or log in.
- **Dashboard:** Once logged in, the dashboard will provide access to employee management features, attendance tracking, leave requests, and performance evaluations.
- **Role-Based Features:** Depending on your role (HR, Manager, or Employee), you will have access to different features.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature-name`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature-name`).
5. Open a pull request describing your changes.


## Contact

For any questions or suggestions, please contact [amitraj4381@gmail.com](mailto:amitraj4381@gmail.com).

---

