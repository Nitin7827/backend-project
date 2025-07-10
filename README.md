# Backend Project

A simple social backend application built with Node.js, Express, MongoDB (Mongoose), and EJS. It supports user registration, authentication, posting, editing, and liking posts.

## Features
- User registration and login with JWT authentication
- Passwords securely hashed with bcrypt
- User profile page displaying posts
- Create, edit, and like/unlike posts
- EJS templating for views

## Project Structure
```
backend project/
  ├── app.js
  ├── models/
  │   ├── post.js
  │   └── user.js
  ├── views/
  │   ├── edit.ejs
  │   ├── index.ejs
  │   ├── login.ejs
  │   └── profile.ejs
  ├── package.json
  └── README.md
```

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone <repo-url>
   cd backend\ project
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Start MongoDB:**
   Ensure MongoDB is running locally on `mongodb://localhost:27017/miniproject`.
4. **Run the app:**
   ```bash
   node app.js
   ```
5. **Access the app:**
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage
- Register a new user on the home page.
- Log in with your credentials.
- Create, edit, and like/unlike posts from your profile page.
- Log out using the logout button.

## Dependencies
- express
- mongoose
- ejs
- bcrypt
- jsonwebtoken
- cookie-parser
