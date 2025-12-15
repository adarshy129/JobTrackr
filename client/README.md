# JobTrackr

JobTrackr is a full-stack job application tracking platform that helps users organize, monitor, and manage their job applications efficiently. It provides secure authentication, a clean dashboard, and full CRUD functionality for job records, making it easier to track application progress across different companies and roles.

The project is designed as a portfolio-ready MERN application, following modern best practices for state management, authentication, and API design.

---

## Key Features

### Authentication & Authorization
- Secure user registration and login
- JWT-based authentication
- Protected routes for authenticated users only

### Demo Login
- Instant demo access without account creation
- Allows recruiters and reviewers to explore the app quickly

### Job Management (CRUD)
- Add new job applications
- Edit existing job details
- Delete job entries
- View all applications in a centralized dashboard

### Job Tracking
- Track application status (e.g. Applied, Interview, Rejected)
- Store company name, position, and other relevant details

### User Experience
- Responsive and clean UI
- Loading states and error handling
- Toast notifications for user feedback

---

## Demo App Usage

JobTrackr includes a **Demo App** option for quick access.

### How to log in using Demo App
1. Open the application
2. Navigate to the Login page
3. Click the **Demo App** button
4. You will be logged in automatically using a predefined test account

> No signup or credentials are required for demo access.

---

## Tech Stack

### Frontend
- React
- Redux Toolkit (state management)
- React Router
- CSS (custom styling)

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose ODM)
- JSON Web Tokens (JWT)

### Other Tools
- Render (deployment)
- Git & GitHub (version control)

---

## Project Structure (High Level)

```
JobTrackr/
│
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── features/       # Redux slices
│   │   └── assets/
│
├── controllers/            # Express controllers
├── routes/                 # API routes
├── models/                 # Mongoose models
├── middleware/             # Auth & error middleware
├── db/                     # Database connection
├── app.js                  # Express app entry
└── package.json
```

---

## Live Demo

https://jobtrackr-dxb9.onrender.com

---

## Getting Started (Local Setup)

### Prerequisites
- Node.js (v16 or later recommended)
- MongoDB (local or Atlas)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/adarshy129/JobTrackr.git
   ```
2. Navigate to the project directory
   ```bash
   cd JobTrackr
   ```
3. Install dependencies
   ```bash
   npm install
   ```

---

## Environment Variables

Create a `.env` file in the root directory and add:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## Running the Application

```bash
npm start
```

The server will start and the application will be available locally.

---

## Security Notes

- Passwords are hashed before storage
- JWT tokens are used for session management
- Protected API routes prevent unauthorized access
- Sensitive configuration values are stored in environment variables

---

## Future Improvements

- Advanced job analytics and statistics
- Search and filter functionality
- Pagination for large job lists
- Role-based access control
- Improved UI animations and theming

---

## Author

**Adarsh Yadav**

GitHub: https://github.com/adarshy129

---

## License

This project is open source and available under the MIT License.
