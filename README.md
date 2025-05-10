# 🎬 Movie Explorer App

**Discover, Search, and Explore Trending Movies Instantly**

---

## 📌 Purpose

The **Movie Explorer App** is a React-based web application designed for movie enthusiasts to **search, view details, and explore trending films** in real time using the [TMDb API](https://developers.themoviedb.org/3). It delivers a user-friendly experience with features like login, favorite movies list, light/dark mode, and infinite scrolling.

---

## 🧭 Overview

This project was built to demonstrate full-stack development capabilities using React, Redux Toolkit, Axios, and MUI (Material UI). The application enables users to:

- Search for any movie and view detailed information.
- Browse trending movies fetched from TMDb.
- Save favorite movies locally.
- View movie cast and trailers.
- Enjoy a responsive design with both **light and dark modes**.

---

## 🎥 Visual Demo

👉 Live App: [Deployed Link](https://aesthetic-daifuku-364cd3.netlify.app/login)

---

## ⚙️ How to Install & Run Locally

1. **Clone the Repository:**
   ```bash
   git clone https://gitlab.com/your-username/movie-explorer.git
   cd movie-explorer
   ```

🧑‍💻 Developer Instructions

    Framework: React with Create React App

    Styling: Material UI (MUI)

    API: TMDb API

    Routing: React Router DOM

    State Management: Redux Toolkit

    Authentication: Firebase Authentication(signup and login)

Features:

    Search and display movies

    Infinite scrolling

    Trending movie section

    Responsive, mobile-first design

Getting Started

This project was bootstrapped with Create React App.
🔧 Available Scripts

In the project directory, you can run:

    npm start – Run in development mode at http://localhost:3000.

    npm run build – Create a production build in the build/ folder.

    npm test – Run tests in watch mode.

    npm run eject – Eject configs (irreversible).

Project Structure

public/
├── index.html
└── assets (favicon, logos, manifest, etc.)

src/
├── components/ # Reusable UI components
├── containers/ # Main pages/screens
├── lib/ # API and helper utilities
├── redux/ # Redux slices and store
├── sagas/ # Redux-Saga files
├── App.js
├── index.js
├── firebase.js
└── config.js

root/
├── package.json
├── .gitignore
├── README.md
