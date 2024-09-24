# StudyNotion - EdTech Platform

## Overview

**StudyNotion** is an EdTech platform designed to empower educators by providing them with an efficient and user-friendly platform to share their skills and knowledge with students. The platform facilitates seamless course creation, management, and student engagement through a variety of features like feedback, ratings, and secure payment options.

## Features

- **User Authentication & Authorization:** Secure identification process using JSON Web Tokens (JWT) for safe user access and data protection.
- **Course Purchase with Razorpay:** Integrated Razorpay payment gateway for secure and hassle-free course purchases.
- **Feedback, Rating, and Reviews:** Enables students to provide feedback, rate, and review courses, helping other learners make informed purchasing decisions based on peer insights.
- **Course Creation & Management:** Instructors can easily create, manage, and publish courses, while students can browse and enroll in courses of their choice.
- **Secure User Management:** Comprehensive user authentication and role-based authorization ensure a safe and personalized learning experience.

## Tech Stack

- **Frontend:** React.js, TailwindCSS, Redux
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Token (JWT)
- **Payment Gateway:** Razorpay

## Installation

To get started with this project, follow the steps below:

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/studynotion-edtech.git

2. Navigate to the project directory:
   ```bash
   cd studynotion-edtech
   
3. Install the dependencies:
   ```bash
   npm install
   
4. Create a `.env` file in the root directory and add the following environment variables:
   - `DATABASE_URI` for MongoDB connection.
   - `JWT_SECRET` for user authentication and token management.
   - `RAZORPAY_KEY_ID` and `RAZORPAY_KEY_SECRET` for Razorpay payment gateway integration.


5. Start the development server:
   ```bash
   npm run dev

## Features Breakdown

- **Authentication & Authorization:**
  - Secured user login and registration with JWT.
  - Role-based access control for students and instructors.

- **Payment Integration:**
  - Razorpay payment gateway for easy course purchases.

- **Course Reviews and Ratings:**
  - Students can provide feedback, rate courses, and leave reviews.
  - Enhances trust and helps others make informed decisions.

