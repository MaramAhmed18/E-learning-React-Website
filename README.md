# E-learning React Website 🎓

<div align="center">

[![Ask DeepWiki](https://devin.ai/assets/askdeepwiki.png)](https://deepwiki.com/MaramAhmed18/E-learning-React-Website)

*🚀 [Live Demo](https://e-learning-react-website-wqti.vercel.app) | 📚 [Documentation](#getting-started) | 🔗 [API](#api)*

A modern, feature-rich e-learning platform built with React

</div>

---

## 🌟 About The Project

Welcome to our comprehensive e-learning platform! This React-based application delivers a dynamic and interactive experience for discovering, managing, and engaging with online courses. Whether you're a student seeking knowledge or an administrator managing content, our platform provides all the tools you need for a seamless learning journey.

### ✨ What Makes It Special

- *🔐 Secure Authentication* - Role-based access control for users and administrators
- *🌍 Multi-language Support* - Seamlessly switch between English and Arabic
- *🎨 Dual Theming* - Light and Dark modes for comfortable viewing
- *📱 Fully Responsive* - Perfect experience across all devices
- *⚡ Fast & Efficient* - Redux state management with localStorage persistence

---

## 🚀 Key Features

### 📖 *Course Discovery*
- Browse extensive course catalog with advanced filtering
- Smart search functionality with real-time results
- Paginated course listings for optimal performance

### 👤 *User Experience*
- *My Courses*: Track your enrolled courses and learning progress
- *Favorites*: Quick access to your preferred courses
- *Wishlist*: Save interesting courses for later
- *Profile*: Personalized dashboard with course history

### ⚙️ *Admin Dashboard*
Complete course management system with:
- ➕ Create new courses
- 📝 Edit existing content
- 🗑️ Remove outdated courses
- 📊 Course analytics and management

### 🌐 *Localization & Accessibility*
- 🇺🇸 English / 🇸🇦 Arabic language support
- 🌓 Light/Dark theme toggle
- 📱 Mobile-first responsive design
- ♿ Accessibility-focused UI components

---

## 🛠️ Built With

<div align="center">

| Technology | Purpose | Version |
|------------|---------|---------|
| ![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black) | Core Framework | Latest |
| ![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white) | State Management | Latest |
| ![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white) | Styling | Latest |
| ![React Router](https://img.shields.io/badge/React_Router-CA4245?style=for-the-badge&logo=react-router&logoColor=white) | Navigation | Latest |

</div>

*Additional Dependencies:*
- **[i18next](https://www.i18next.com/)** - Internationalization framework
- **[Axios](https://axios-http.com/)** - HTTP client for API requests

---

## 🚀 Getting Started

### 📋 Prerequisites

Ensure you have the following installed:

bash
# Check Node.js version (requires v14+)
node --version

# Check npm version
npm --version


If not installed, download from [Node.js Official Website](https://nodejs.org/)

### ⚡ Quick Start

1. *Clone the repository*
   bash
   git clone https://github.com/maramahmed18/e-learning-react-website.git
   

2. *Navigate to project directory*
   bash
   cd e-learning-react-website
   

3. *Install dependencies*
   bash
   npm install
   

4. *Start development server*
   bash
   npm start
   

5. *Open your browser*
   
   Navigate to [http://localhost:3000](http://localhost:3000)

🎉 *That's it!* Your local development server is now running.

---

## 📜 Available Scripts

| Command | Description |
|---------|-------------|
| npm start | 🔥 Runs development server with hot reload |
| npm run build | 📦 Creates optimized production build |
| npm test | 🧪 Launches interactive test runner |
| npm run eject | ⚠️ Ejects from Create React App (irreversible) |

---

## 🔌 API Reference

This project integrates with a mock API powered by **[Retool](https://retool.com/)** for comprehensive course data management.

### 🌐 Base URL

https://retoolapi.dev/dL2nNn/data


### 📡 Available Endpoints

| Method | Endpoint | Description | Example |
|--------|----------|-------------|---------|
| GET | /data | Fetch all courses | GET /data |
| GET | /data?course_name_like={query} | Search courses | GET /data?course_name_like=react |
| GET | /data/{id} | Get course by ID | GET /data/1 |
| POST | /data | Create new course | POST /data |
| PUT | /data/{id} | Update course | PUT /data/1 |
| DELETE | /data/{id} | Delete course | DELETE /data/1 |

### 📋 Sample Response
json
{
  "id": 1,
  "course_name": "React Fundamentals",
  "description": "Learn React from scratch",
  "instructor": "John Doe",
  "duration": "40 hours",
  "level": "Beginner"
}


---

## 🤝 Contributing

Contributions make the open-source community an amazing place to learn and grow! Any contributions you make are *greatly appreciated*.

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License. See LICENSE file for details.

---

## 👨‍💻 Author

*Maram Ahmed*
- GitHub: [@MaramAhmed18](https://github.com/maramahmed18)
- Project Link: [E-learning React Website](https://github.com/maramahmed18/e-learning-react-website)

---

<div align="center">

*⭐ Don't forget to star this repository if you found it helpful!*

*[🚀 Live Demo](https://e-learning-react-website-wqti.vercel.app)* | **[📝 Report Bug](https://github.com/maramahmed18/e-learning-react-website/issues)** | **[💡 Request Feature](https://github.com/maramahmed18/e-learning-react-website/issues)**

</div>
