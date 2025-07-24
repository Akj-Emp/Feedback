# 🗣️ VoicY - Feedback & Testimonial Web App

VoicY is a simple yet powerful feedback/testimonial web application built using **Node.js**, **Express**, **MongoDB**, and **EJS** templating engine. Users can register, log in, and submit feedback, which is displayed publicly. Feedback can also be liked or disliked by others, with per-user restrictions in place.

---

## 🚀 Features

- 🧑 User registration and login (with session-based Passport.js authentication)
- 📝 Submit feedback/testimonials (only when logged in)
- 📃 View all feedback publicly
- 👍 Like or 👎 Dislike feedback (only once per user, cannot do both)
- ⚠️ Server-side validation and flash-based user notifications
- 🌈 Beautiful and responsive UI (Bootstrap 5)

---

## 🏗️ Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, Bootstrap 5
- **Database**: MongoDB Atlas with Mongoose
- **Authentication**: Passport.js (LocalStrategy)
- **Session Management**: express-session
- **Flash Messaging**: connect-flash
- **Password Hashing**: bcryptjs

---

## 📂 Folder Structure

