# Netflix Clone 🎬

**A responsive, React-powered frontend for a Netflix-like streaming experience.**

## ✨ Live Demo & Screenshots
<img width="1913" height="1003" alt="image" src="https://github.com/user-attachments/assets/026f89f9-6a17-4cb7-b342-77356480cc4c" />
<img width="1917" height="891" alt="image" src="https://github.com/user-attachments/assets/366b9bbf-86ff-42ba-b0d9-c73e9d2680dd" />

---
<img width="1919" height="946" alt="image" src="https://github.com/user-attachments/assets/5e8fb4fe-a403-43f7-90da-475c262f5cc5" />


## 🌟 Project Overview

This project is a modern web application designed to mimic the core user interface and Browse experience of Netflix. Built with a focus on a responsive design and dynamic content fetching, it serves as a robust foundation for understanding frontend development, API integration, and user authentication in a practical context.

It leverages client-side React for an interactive user interface, styled efficiently with Tailwind CSS for a mobile-first approach. User management is handled by Firebase, while real movie and TV show data is pulled directly from The Movie Database (TMDB) API.

## 🚀 Features

* **Secure User Authentication:**
    * **Email & Password:** Robust user signup and login through Firebase Authentication.
    * **Google Sign-In:** Seamless one-click login via Google OAuth.
    * **Anonymous Access:** (Optional) Allows quick demo access without full registration.
* **Dynamic Content Delivery:**
    * **Hero Billboard:** A prominent, randomly selected movie or show with rich details on the homepage, powered by TMDB's trending data.
    * **Interactive Carousels:** Multiple categorized rows ("Trending Now," "Top Rated Movies," "Action Movies," "Comedy Movies") displaying movie posters with smooth horizontal scrolling.
    * **Image Fallbacks:** Graceful handling for missing movie posters or backdrops.
* **Responsive UI:** Crafted with Tailwind CSS to ensure a consistent and appealing experience across desktops, tablets, and mobile devices.
* **Persistent User Data:** Utilizes Firebase Firestore to store user-specific information, laying the groundwork for features like "My List."
* **Intuitive Navigation:** A dynamic header that adapts on scroll, providing easy access to different sections.

## 📦 Technologies & Ecosystem

* **Frontend Library:** [React 17](https://react.dev/) - For building component-based user interfaces.
* **Styling Framework:** [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.
* **JavaScript Compiler:** [Babel Standalone](https://babeljs.io/docs/en/babel-standalone) - For on-the-fly JSX compilation directly in the browser.
* **Authentication & Database:** [Firebase](https://firebase.google.com/)
    * `firebase/auth`: For robust user authentication services.
    * `firebase/firestore`: For cloud-hosted NoSQL database to store user-specific data.
* **Data Source:** [The Movie Database (TMDB) API](https://developers.themoviedb.org/3/getting-started/introduction) - A comprehensive source for movie, TV show, and actor information.

## ⚙️ Setup & Local Development

Follow these simple steps to get the Netflix Clone running on your local machine.

### Prerequisites

* **Git:** Make sure Git is installed on your system.
* **Web Browser:** A modern web browser (Chrome, Firefox, Edge, Safari).
* **Node.js & npm (or npx):** For easily running a local server.

### 1. Clone the Repository

```bash
git clone [https://github.com/](https://github.com/)[YOUR_USERNAME]/netflix-clone.git
cd netflix-clone
