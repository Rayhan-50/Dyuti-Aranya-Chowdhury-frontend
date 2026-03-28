# 🇧🇩 Dyuti Aranya Chowdhury (Preeti) - Election Campaign Platform 2025 🗳️

> **A modern, full-stack digital campaign and public engagement platform for Bangladesh Election 2025.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-View_Site-success?style=for-the-badge&logo=vercel)](https://your-live-link.com)
[![Frontend](https://img.shields.io/badge/Frontend-React_19-blue?style=for-the-badge&logo=react)]()
[![Backend](https://img.shields.io/badge/Backend-Node.js-green?style=for-the-badge&logo=node.js)]()

---

## 📖 Project Context

This system is built for **Bangladesh Election 2025** to represent a political leader's campaign platform. It serves as a bridge between the political leader and the citizens, promoting transparency, awareness, and public engagement through a scalable digital presence.

---

## 📸 Screenshots
*(Add your screenshots here)*
> `<img src="placeholder.png" alt="Home Page" width="800">`

---

## 💻 Frontend Section (Client)

The client-side is a responsive, fast, and interactive web application built with modern React.

### 🛠️ Technologies Used
- **React 19 & Vite** - Core framework & bundler
- **Tailwind CSS v4** - Styling & responsive design
- **Framer Motion** - Smooth UI animations
- **React Router v7** - Client-side routing
- **Firebase** - Authentication & real-time features
- **React Query & Axios** - Data fetching and state management

### ✨ Key Features
- **Responsive UI:** Seamless experience across desktop and mobile devices.
- **Campaign Dashboard:** Display candidate's vision, journey, and latest news.
- **Voter Engagement:** Interactive community sections and registration portals.
- **Secure Authentication:** Firebase-powered login and sign-up for supporters.

### 📂 Folder Structure
```text
src/
 ├── components/       # Reusable UI components
 ├── pages/            # Page components (Home, SignUp, etc.)
 ├── hooks/            # Custom React hooks (e.g., useAdmin)
 ├── routes/           # Routing configuration
 └── assets/           # Static files and images
```

### 🚀 Installation Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/dyuti-aranya-chowdhury.git
   cd dyuti-aranya-chowdhury
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Configure Environment Variables:**
   Create a `.env.local` file in the root directory and add your Firebase credentials:
   ```env
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_project_id
   ...
   ```
4. **Run the development server:**
   ```bash
   npm run dev
   ```

---

## ⚙️ Backend Section (Server)

The server-side provides a robust RESTful API for managing user data, campaigns, and overall platform administration. 
*(See the `dyuti-aranya-chowdhury-server` directory for full backend code and README)*

### 🛠️ Technologies Used
- **Node.js & Express.js** - Server engine and framework
- **MongoDB** - NoSQL Database for scalable data storage
- **Dotenv** - Environment variable management
- **CORS** - Cross-origin resource sharing

### 🔌 API Features
- **User Authentication:** Secure verification and role assignment (Admin/User).
- **ভোটার/সমর্থক ডেটা ম্যানেজমেন্ট (Voter/Supporter Data Management):** Handle registrations, profiles, and queries safely.
- **Campaign Data Handling:** Manage news updates, events, and community posts dynamically.

### 📡 API Endpoints (Overview)
- `POST /api/auth/register` - Register a new supporter
- `POST /api/auth/login` - User/Admin login
- `GET /api/users` - Fetch user details (Admin only)
- `GET /api/campaigns` - Fetch latest campaign news

---

## 🎯 Features & Architecture

- **Secure Authentication:** Role-based access control distinguishing between Admin and regular Users.
- **Scalable Architecture:** Component-driven frontend with a decoupled RESTful Express API.
- **Dynamic Updates:** Real-time feedback and dynamic routing for campaign news.
- **Interactive UI:** Meaningful animations and accessible forms.

---

## 💡 Purpose of the Project

- **Digital Campaign Management:** Modernize the election journey through a centralized online hub.
- **Public Engagement Platform:** Connect directly with voters and supporters.
- **Awareness & Transparency:** Provide verifiable information, news, and goals directly to the public.

---

## 🚀 Future Improvements

- [ ] **Mobile App Integration:** Extend the platform to native iOS and Android apps.
- [ ] **Analytics Dashboard:** Advanced charting and metrics for campaign organizers to track engagement.
- [ ] **AI-Based Voter Insights:** Implement machine learning to analyze community sentiment and feedback.

---

## 👨‍💻 Author

- **Name:** Rayhan Ahmed
- **Role:** Full Stack / MERN Developer
- **Contact:** 
  - GitHub: [@Rayhan-50](https://github.com/Rayhan-50)
  - Email: [rayhanahmed.nstu@gmail.com](mailto:rayhanahmed.nstu@gmail.com)
  - LinkedIn: [Rayhan Ahmed](https://www.linkedin.com/in/rayhan-ahmed-0ab5aa33a/)

---
*Made with ❤️ for Bangladesh Election 2025.*