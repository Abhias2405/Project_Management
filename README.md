<div align="center">
  <br />
  <div>
    <img src="https://img.shields.io/badge/-Next.js-black?style=for-the-badge&logoColor=white&logo=nextdotjs&color=000000" alt="nextjs" />
    <img src="https://img.shields.io/badge/-PostgreSQL-black?style=for-the-badge&logoColor=white&logo=postgresql&color=4169E1" alt="postgresql" />
    <img src="https://img.shields.io/badge/-Prisma-black?style=for-the-badge&logoColor=white&logo=prisma&color=2D3748" alt="prisma" />
    <img src="https://img.shields.io/badge/-Tailwind_CSS-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="tailwindcss" />
    <img src="https://img.shields.io/badge/-AWS-black?style=for-the-badge&logoColor=white&logo=amazonaws&color=232F3E" alt="aws" />
  </div>
  <h3 align="center">Project Management Dashboard</h3>
   <div align="center">
     A comprehensive project management solution built with Next.js and AWS
    </div>
</div>

## 📋 Table of Contents
1. 🤖 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🔋 [Features](#features)
4. 🤸 [Quick Start](#quick-start)
5. 🚀 [Deployment](#deployment)
6. 🛠️ [Environment Setup](#environment)

## <a name="introduction">🤖 Introduction</a>
A full-stack project management dashboard built with Next.js and AWS services. Features include task management, team collaboration, and real-time project tracking with robust cloud infrastructure.

## <a name="tech-stack">⚙️ Tech Stack</a>
### Frontend
- Next.js
- Tailwind CSS
- Redux Toolkit with RTK Query
- Material UI Data Grid

### Backend
- Node.js with Express
- Prisma ORM
- PostgreSQL

### Cloud Infrastructure
- AWS EC2 for hosting
- AWS RDS for database
- AWS S3 for storage
- AWS Cognito for authentication
- AWS API Gateway
- AWS Lambda
- AWS Amplify

## <a name="features">🔋 Features</a>
👉 **Project Tracking**: Real-time project status and progress monitoring  
👉 **Task Management**: Create, assign, and track tasks  
👉 **Team Collaboration**: Team member management and role assignments  
👉 **Data Visualization**: Gantt charts and project analytics  
👉 **Cloud Storage**: AWS S3 integration for file management  
👉 **Authentication**: Secure user authentication via AWS Cognito  
👉 **Database Management**: PostgreSQL with Prisma ORM  
👉 **Responsive Design**: Mobile-first approach with Tailwind CSS

## <a name="quick-start">🤸 Quick Start</a>

### Prerequisites
- Node.js
- PostgreSQL
- AWS Account
- Git

### Installation

1. **Clone and Install**
```bash
git clone https://github.com/Abhias2405/Project_Management
cd project-management

# Install Frontend Dependencies
cd client
npm install

# Install Backend Dependencies
cd ../server
npm install
```

2. **Database Setup**
```bash
npx prisma generate
npx prisma migrate dev --name init
npm run seed
```

## <a name="deployment">🚀 Deployment</a>
The application utilizes AWS services:
- Frontend: AWS Amplify
- Backend: AWS EC2
- Database: AWS RDS
- Storage: AWS S3
- Authentication: AWS Cognito
- API Management: AWS API Gateway

## <a name="environment">🛠️ Environment Setup</a>

### Backend (.env)
```plaintext
PORT=
DATABASE_URL=
AWS_REGION=
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
COGNITO_USER_POOL_ID=
COGNITO_CLIENT_ID=
```

### Frontend (.env.local)
```plaintext
NEXT_PUBLIC_API_BASE_URL=
NEXT_PUBLIC_AWS_REGION=
NEXT_PUBLIC_COGNITO_USER_POOL_ID=
NEXT_PUBLIC_COGNITO_CLIENT_ID=
```
