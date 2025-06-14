# Course Recommendation System

A full-stack web application built with the MERN stack that allows admins to post courses and upload videos, and students to browse, purchase, and watch courses. The system recommends courses to students based on selected categories and various recommendation algorithms.

---

## Features

- **User Authentication:** Separate login for Admin and Student roles using JWT.
- **Admin Panel:** Admin can create, update, delete courses and upload course videos.
- **Course Browsing:** Students can browse courses by categories such as Web Development, Machine Learning, Cyber Security, etc.
- **Purchase Courses:** Students can buy courses securely via integrated payment gateway (kHALTI/ESEWA).
- **Video Playback:** Students can watch purchased course videos with progress tracking.
- **Course Recommendations:** Recommend similar courses based on selected category and user preferences.
- **Multiple Recommendation Algorithms:** Content-based, collaborative filtering (user & item based), hybrid approaches planned.

---

## Tech Stack

| Layer              | Technology                             |
|--------------------|--------------------------------------|
| Frontend           | React.js, React Router, Axios, Tailwind CSS / Material UI |
| Backend            | Node.js, Express.js, MongoDB, Mongoose, JWT Authentication, Multer (for file uploads) |
| Video Storage      | AWS S3 / Cloudinary / Local Storage  |
| Payment Gateway    | Khalti | Esewa
| Recommendation     | Custom algorithms implemented in Node.js |


---

## Installation & Setup

### Backend
PORT=5000   | 
MONGO_URI=your_mongodb_connection_string


1. Clone the repo:
   ```bash
   git clone https://github.com/yourusername/course-recommendation-system.git
   cd course-recommendation-system/backend
