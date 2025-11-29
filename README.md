🌍 Wanderlust – A MERN Stack Travel Blog (Deployed on Kubernetes)

A learning-focused open-source project by Souvik De

Wanderlust is a simple yet practical MERN travel blog website, designed for developers who want to learn the MERN stack, master Git/GitHub workflows, and explore DevOps concepts like Docker & Kubernetes.

Whether you're a beginner or an experienced developer — this project will help you learn, build, and deploy.

🎯 Project Goals
1. Kickstart Your Open Source Journey

This project will help you learn:

How to contribute to open source

How to use Git & GitHub professionally

How to work inside a MERN codebase

2. Strengthen Your MERN & React Skills

Wanderlust includes:

React fundamentals → forms, routing, components

MERN API integration

Improvements planned → caching, SSR, performance, and more

🧑‍💻 Author

👤 Name: Souvik De
💼 Role: Senior Web Developer (Laravel, Node.js, MERN, DevOps Learner)
📌 GitHub: https://github.com/souvikde319

🚀 Focus Areas: MERN, Node.js, Kubernetes, Docker, Terraform, DevOps projects

⚙️ Setting Up the Project Locally
🚀 Backend Setup

1. Clone the Repository
git clone https://github.com/{your-username}/MERN-application-deployed-kubernetes.git

git clone https://github.com/{your-username}/MERN-application-deployed-kubernetes.git
Go to Backend Folder

bash
Copy code
cd backend
Install Dependencies

bash
Copy code
npm i
MongoDB Setup
Connect to:

arduino
Copy code
mongodb://localhost:27017
Import Sample Data (Optional)

bash
Copy code
mongoimport --db wanderlust --collection posts --file ./data/sample_posts.json --jsonArray
Set Environment Variables

bash
Copy code
cp .env.sample .env
Start Backend

bash
Copy code
npm start
Expected:

csharp
Copy code
[BACKEND] Server is running on port 5000
[BACKEND] Database connected: mongodb://127.0.0.1/wanderlust
💻 Frontend Setup
Open new terminal & go to frontend:

bash
Copy code
cd frontend
Install deps:

bash
Copy code
npm i
Copy env:

bash
Copy code
cp .env.sample .env.local
Start server:

bash
Copy code
npm run dev
🐳 Run with Docker
Make sure Docker & Docker Compose are installed

Clone the repo:

bash
Copy code
git clone https://github.com/{your-username}/MERN-application-deployed-kubernetes.git
Go to project:

bash
Copy code
cd wanderlust
Update .env.sample if server IP changes

Run Docker:

bash
Copy code
docker-compose up
Your backend + frontend will build & run automatically.

⭐ Support the Project
If you find this project useful, please consider:

➡️ Starring the repository
➡️ Sharing it with other MERN learners
➡️ Contributing with features, bugs, or improvements

Your support motivates continued updates and Kubernetes-based enhancements 💙

## 🛠️ Tech Stack & Tools

![Node.js](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white)

![VS Code](https://img.shields.io/badge/VSCode-0078d7?style=for-the-badge&logo=visual-studio-code&logoColor=white)

