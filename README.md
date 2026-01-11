# Invertea Learners - Online Learning Platform

Welcome to **Invertea Learners**, a comprehensive online learning platform designed to provide quality education accessible to everyone, anywhere. This project showcases a modern, responsive, and user-friendly interface for students to browse courses, access notes, test their skills with quizzes, and connect with expert instructors.

![Invertea Learners Banner](images/home/student.png)

## 🌟 Features

-   **Responsive Design**: Fully optimized for Desktop, Tablet, and Mobile devices.
-   **Modern UI/UX**: Clean, professional, and vibrant interface using custom CSS variables.
-   **Course Catalog**: Browse a wide range of courses (HTML, CSS, JS, React, Python, ML, etc.).
-   **Interactive Elements**:
    -   Smooth scrolling navigation.
    -   Dynamic "View All" courses toggle.
    -   OwlCarousel sliders for Partners and Testimonials.
-   **Functional Cart System**: 
    -   Add items to cart with persistence (Local Storage).
    -   Dynamic price calculation and item removal.
    -   Visual cart page with distinct "Empty" and "Filled" states.
-   **Quiz Hub**: 
    -   Interactive quiz games for HTML, CSS, JS, and Python.
    -   Real-time scoring and progress tracking.
-   **Login Page**: Sleek and responsive user authentication interface.
-   **Notes Section**: Easy access to downloadable PDF notes.
-   **Testimonials**: Realistic student feedback sections with professional visuals.

## 🚀 Technologies Used

-   **HTML5**: Semantic structure.
-   **CSS3**: Custom properties (variables), Flexbox, Grid, Animations.
-   **JavaScript (Vanilla)**: DOM manipulation, Event listeners, Local Storage logic, Quiz Game engine.
-   **JQuery**: Required for OwlCarousel.
-   **OwlCarousel**: For sliding carousels (Partners, Testimonials).
-   **FontAwesome**: For icons.

## 👥 Team Members

This project was built with passion by the Invertea Learners team:

-   **Abhishek Maheshwari** (Team Leader)
-   Abhishek Verma
-   Abhishek Kumar
-   Pankaj Kumar
-   Ankit
-   Rinku
-   Chaht

*(Special thanks to my AI assistant for helping polish the code and UI!)*

## 🛠️ How to Deploy on Vercel

This project is optimized for deployment on Vercel.

1.  **Push to GitHub**:
    -   Initialize git: `git init`
    -   Add files: `git add .`
    -   Commit changes: `git commit -m "Final version for presentation"`
    -   Push to your repo: `git push origin main`

2.  **Login to Vercel**: 
    -   Go to [vercel.com](https://vercel.com) and login with your GitHub account.

3.  **Add New Project**: 
    -   Click "Add New..." -> "Project".

4.  **Import Repository**: 
    -   Select `Invertea_Learner_Website`.

5.  **Deploy**: 
    -   Vercel will automatically detect the `index.html` and deploy your site.

6.  **Done!** Your website is now live and can be shared with teachers and friends.

## 📂 Project Structure

```
InverteaLearners/
├── index.html        # Main landing page with Course listing & Testimonials
├── style.css         # Global styles and variables
├── script.js         # Main logic and carousel init
├── login.html        # Login page
├── cart.html         # Cart page with LocalStorage logic
├── cart.css          # Cart specific styles
├── all_courses.html  # Additional courses page
├── quiz.html         # Quiz Hub (Topic Selection)
├── quiz-play.html    # Interactive Quiz Game Engine
├── images/           # Detailed image assets
├── notes/            # PDF resources
└── quizs/            # Legacy quiz resources
```

## 📝 License

This project is for educational purposes. All rights reserved by **Invertea Learners**.
