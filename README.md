# Instinctive Full Stack Task

## Overview
The **Instinctive Full Stack Task** is a comprehensive CRUD application designed to manage and explore data efficiently. It integrates advanced state management with a modern and responsive UI for a seamless user experience. The project demonstrates the use of a full-stack technology suite, offering robust backend functionality coupled with a dynamic frontend.

---

## Key Features

- **CRUD Operations:** Complete implementation of Create, Read, Update, and Delete functionalities for efficient data management.
- **Table Filtering:** Integrated filtering to allow users to explore and manage data effortlessly.
- **State Management with Redux:** Leveraged Redux for centralized and efficient state management during data fetching and updates.
- **Responsive Design:** Built a reusable and responsive UI using **Tailwind CSS** and **ShadCN**, ensuring compatibility across devices.

---

## Tech Stack

- **Frontend:** React JS  
- **Backend:** Node JS  
- **Database:** Supabase  
- **ORM:** Prisma  
- **State Management:** Redux  
- **Styling:** Tailwind CSS  

---

## Screenshots
![image](https://github.com/user-attachments/assets/20dbae68-83a9-4771-9f99-b7a3eca67a7b)

---

## Running the Project Locally

Follow these steps to set up and run the application on your local machine:

### Clone the Repository
```bash
git clone https://github.com/abhijha910/Instinctive-Full-Stack-task-main.git
```

### Navigate to the Project Directory
```bash
cd Instinctive-Full-Stack-task-main
```

## Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd server
   ```

2. Install backend dependencies:
   ```bash
   npm install
   ```

3. Start the backend server:
   ```bash
   npm start
   ```

## Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd client
   ```

2. Install frontend dependencies:
   ```bash
   npm install
   ```

3. Start the frontend server:
   ```bash
   npm run dev
   ```

## Environment Variables

Make sure the following environment variables are set correctly for both the backend and frontend:

### For Backend:
```bash
DATABASE_URL - MongoDB connection URL
```
```bash
DIRECT_URL - Direct connection URL for Prisma
```
```bash
CORS_ORIGIN - Allowed origins for Cross-Origin Resource Sharing
```
```bash
PORT - Port for the backend server
```

### For Frontend:
```bash
VITE_BASE_URL - Base URL for API calls
```
