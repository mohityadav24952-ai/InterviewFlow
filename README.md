<div align="center">

# 💼 InterviewFlow

### Intelligent Technical Interview Platform

Conduct real-world technical interviews with **Live Coding, Video Calling, Screen Sharing, Real-Time Collaboration, and AI-Assisted Evaluation** — all in one platform.

![Next.js](https://img.shields.io/badge/Next.js-000?style=for-the-badge&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=for-the-badge)
![WebRTC](https://img.shields.io/badge/WebRTC-333333?style=for-the-badge)
![AI Powered](https://img.shields.io/badge/AI-Powered-blue?style=for-the-badge)

⭐ If you like this project, consider giving it a star!

</div>

---

# 📖 Overview

InterviewFlow is a modern full-stack technical interview platform built to simplify software engineering interviews.

Instead of switching between multiple tools for video calls, coding assessments, communication, and evaluation, InterviewFlow brings everything together into one seamless experience.

It provides interviewers with an efficient hiring workflow while helping candidates perform coding interviews in a realistic environment.

---

# ✨ Key Features

## 🔐 Authentication & User Management

- Secure JWT Authentication
- Role-Based Access
- Protected Routes
- User Registration & Login
- Session Management

---

## 📅 Interview Management

- Schedule Interviews
- Join Interview Sessions
- Interview Dashboard
- Candidate Dashboard
- Interview History

---

## 💻 Live Coding Environment

- Monaco Code Editor
- Multi-Language Support
- Real-Time Collaborative Coding
- Code Execution
- Syntax Highlighting
- Custom Input & Output

---

## 🎥 Video Conferencing

- HD Video Calling
- Audio Controls
- Camera Toggle
- Participant Management
- Low-Latency Communication

---

## 🖥 Screen Sharing

- Full Screen Sharing
- Window Sharing
- Browser Tab Sharing
- Live Collaboration

---

## 💬 Real-Time Communication

- Live Chat
- Instant Messaging
- Interview Notes
- Socket.io Powered Events

---

## 🤖 AI Features

- AI-Generated Technical Questions
- Resume-Based Interview Questions
- Coding Performance Analysis
- AI Interview Feedback
- Personalized Improvement Suggestions

---

## 📊 Analytics Dashboard

### Interviewer

- Candidate Reports
- Performance Tracking
- Hiring Recommendations
- Interview Analytics

### Candidate

- Previous Interviews
- Coding Performance
- AI Feedback Reports
- Skill Progress Tracking

---

# 🛠 Tech Stack

## Frontend

- Next.js
- React.js
- TypeScript
- Tailwind CSS
- Monaco Editor

## Backend

- Node.js
- Express.js
- MongoDB
- REST APIs
- JWT Authentication

## Real-Time

- Socket.io
- WebRTC

## AI

- Gemini API / OpenAI API

---

# 🏗 Architecture

```
                Frontend (Next.js)

                       │

               REST API + Socket.io

                       │

              Express.js Backend

          ┌──────────┴──────────┐

      MongoDB              AI Services

          │                     │

      User Data         Interview Intelligence
```

---

# 📂 Project Structure

```text
InterviewFlow/

├── frontend/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   ├── services/
│   └── utils/
│
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── sockets/
│   └── services/
│
└── README.md
```

---



# ⚙ Environment Variables

## Backend (`/backend/.env`)

```env
PORT=3000
NODE_ENV=development

DB_URL=your_mongodb_connection_url

JWT_SECRET=your_secret

OPENAI_API_KEY=your_api_key

CLIENT_URL=http://localhost:3000
```

---

## Frontend (`/frontend/.env`)

```env
NEXT_PUBLIC_API_URL=http://localhost:3000/api

NEXT_PUBLIC_SOCKET_URL=http://localhost:3000
```

---

# 🚀 Installation

```bash
git clone https://github.com/yourusername/interviewflow.git

cd interviewflow
```

---

# 🔧 Run Backend

```bash
cd backend

npm install

npm run dev
```

---

# 💻 Run Frontend

```bash
cd frontend

npm install

npm run dev
```

---

# 🌟 Future Improvements

- AI Voice Analysis
- AI Proctoring
- Whiteboard Collaboration
- Calendar Integration
- Multi-Round Interviews
- Company Dashboard
- Interview Templates
- Coding Contest Mode
- Automated Hiring Score

---

# 💡 Why InterviewFlow?

Traditional interview platforms primarily focus on communication.

InterviewFlow combines **coding, communication, collaboration, and AI-powered evaluation** into one integrated platform that closely replicates real-world software engineering interviews.

Rather than simply hosting interviews, it helps organizations make **better technical hiring decisions** through intelligent assessment workflows.

---

# 🤝 Contributing

Contributions, feature requests, and pull requests are always welcome.

If you have ideas to improve InterviewFlow, feel free to fork the repository and submit a PR.

---

# ⭐ Support

If you found this project useful, don't forget to leave a ⭐ on GitHub.

It motivates further development and helps others discover the project.

---

<div align="center">

Made with ❤️ by Mohit Kumar Yadav

</div>
