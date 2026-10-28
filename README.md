# Job Hunt – MERN Stack Job Portal

A full-stack job portal built using the MERN stack that connects job seekers with recruiters. Users can explore job opportunities, apply for jobs, and manage their profiles, while recruiters can post jobs and manage applications.

## 🚀 Tech Stack

- **Frontend:** React.js, Vite, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **Authentication:** JWT, Cookies, bcrypt
- **File Uploads:** Cloudinary
- **Email Services:** Nodemailer

## ✨ Features

- User registration and authentication
- Browse and search for jobs
- Apply for job opportunities
- Recruiter and company management
- Post and manage job listings
- Track and manage applications
- Upload profile images and documents
- AI-powered job recommendations

## 📁 Project Structure

```text
JOB-PORTAL-PROJECT/
├── Backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── index.js
│   └── package.json
│
├── Frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── .gitignore
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd JOB-PORTAL-PROJECT
```

### 2. Setup Backend

```bash
cd Backend
npm install
```

Create a `.env` file using `example.env` and configure your MongoDB connection, authentication secret, Cloudinary credentials, email credentials, and other required environment variables.

Start the backend:

```bash
npm run dev
```

### 3. Setup Frontend

Open a new terminal:

```bash
cd Frontend
npm install
npm run dev
```

Open the local URL displayed in your terminal to access the application.

## 🔐 Environment Variables

Configure the required environment variables in `Backend/.env`. Refer to `Backend/example.env` for the variable names and placeholders.

**Important:** Never commit your actual API keys, database credentials, or other secrets to GitHub.

## 👨‍💻 Contributors

- Abhinav Sharma
- Abhay Kumar Kanwadia
- Akshat Parashar

## 🎯 Project Objective

To develop a user-friendly job portal that simplifies job searching, recruitment, and application management through a modern web application.

---

⭐ If you find this project useful, consider giving the repository a star!
