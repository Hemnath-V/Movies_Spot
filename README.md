# 🎬 Movie Spot

A modern and beginner-friendly movie application built with **React.js**, **Appwrite**, and **Tailwind CSS**.

🌐 Live Demo: [Movie Spot](https://my-movie-spot.netlify.app/)  
📦 GitHub Repository: [Movies_Spot](https://github.com/Hemnath-V/Movies_Spot)

---

## 📋 Table of Contents

- [🤖 Introduction](#-introduction)  
- [⚙️ Tech Stack](#️-tech-stack)  
- [🔋 Features](#-features)  
- [🤸 Quick Start](#-quick-start)  

---

## 🤖 Introduction

Welcome to **Movie Spot** 🎥 – A sleek and modern interface to browse and discover movies built for learning and fun.

This project was developed by following the amazing tutorial from **JavaScript Mastery**. It helps beginners understand React.js, API integration, styling with Tailwind CSS, and backend services with Appwrite.

---

## ⚙️ Tech Stack

- ⚛️ **React.js** – for building the interactive and dynamic user interface.
- 🧩 **Appwrite** – used as the backend-as-a-service platform to manage authentication, database, and server-side functions.
- 🎨 **Tailwind CSS** – utility-first CSS framework for fast, modern, and responsive UI design.
- 🎬 **TMDb API (The Movie Database)** – used to fetch and display real-time movie data, including titles, posters, and ratings.

---

## 🔋 Features

- 🔍 **Browse All Movies** – Explore a collection of popular movies  
- 🎯 **Search Movies** – Use the search bar to quickly find your favorite titles  
- 📈 **Trending Algorithm** – Displays trending titles using a dynamic algorithm  
- 💡 **Modern UI/UX** – Sleek, clean, and visually appealing layout  
- 📱 **Responsive Design** – Mobile-friendly across all devices  
- 🧱 **Reusable Components** – Clean code architecture for scalability  

---

## 🤸 Quick Start

Ready to dive in? Follow these steps to get Movie Spot up and running locally on your machine. 🚀

---

### 📦 1. Clone the Repository

Use Git to clone the project to your local development environment:

```bash
git clone https://github.com/Hemnath-V/Movies_Spot.git
cd Movies_Spot

# 🛠 2. Install Dependencies
npm install  # Install project dependencies

# 🧑‍💻 3. Set Up Environment Variables
# Create and open the environment file
touch .env.local  # (If not already created)

# Add the following credentials inside .env.local
# Replace the placeholder values with your actual credentials from TMDb and Appwrite
VITE_IMDB_API_KEY=YOUR_IMDB_API_KEY               # Your TMDb API key
VITE_APPWRITE_PROJECT_ID=YOUR_APPWRITE_PROJECT_ID # Appwrite project ID
VITE_APPWRITE_DATABASE_ID=YOUR_APPWRITE_DATABASE_ID # Appwrite database ID
VITE_APPWRITE_COLLECTION_ID=YOUR_APPWRITE_COLLECTION_ID # Appwrite collection ID

# 🧪 4. Test Setup
npm run lint  # Run linter to check code style
# or
npm test      # Run unit tests

# 🚀 5. Start Development Server
npm run dev  # Start the development server

http://localhost:5173  # View your app in the browser


Now, all the headings are included as part of the comments inside the code blocks. Let me know if you need further adjustments!
