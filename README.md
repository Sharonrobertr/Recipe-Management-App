# Recipe Management App

## 📌 Project Overview
A full-stack Recipe Management App with **ASP.NET Core Web API (backend)** and **React (frontend)**.  
It allows users to create, manage, and share recipes with authentication, search, and filtering.

---

## 🛠 Tech Stack
- **Frontend:** React, JavaScript, Bootstrap/Tailwind (if used)
- **Backend:** ASP.NET Core Web API
- **Database:** SQL Server
- **Authentication:** JWT (JSON Web Token)
- **Hosting:** (Add details if deploying)

---

# 🚀 Getting Started

## 🔹 Backend Setup (ASP.NET Core Web API)

### 1️⃣ Prerequisites
- [.NET SDK](https://dotnet.microsoft.com/download) (Version X.X)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)
- Git

### 2️⃣ Clone the Repository
```sh
git clone https://github.com/Sharonrobertr/Recipe-Management-App.git
cd Recipe-Management-App/backend  # Navigate to backend folder
```

### 3️⃣ Setup Environment Variables
Create an **`appsettings.json`** file in the backend root directory:
```json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER;Database=RecipeDB;User Id=YOUR_USER;Password=YOUR_PASSWORD;"
  }
}
```

### 4️⃣ Install Dependencies
```sh
dotnet restore
```

### 5️⃣ Apply Database Migrations
```sh
dotnet ef database update
```

### 6️⃣ Run the API Server
```sh
dotnet run
```
The API will be available at `http://localhost:5000` (or `https://localhost:5001`).

---

## 🔹 Frontend Setup (React)

### 1️⃣ Prerequisites
- [Node.js](https://nodejs.org/) (LTS version recommended)
- NPM or Yarn

### 2️⃣ Navigate to the Frontend Folder
```sh
cd ../frontend
```

### 3️⃣ Install Dependencies
```sh
npm install
```

### 4️⃣ Start the Frontend Server
```sh
npm start
```
Runs the app in development mode. Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📌 API Endpoints (Backend)
| Method | Endpoint | Description |
|--------|---------|-------------|
| GET    | `/api/recipes` | Get all recipes |
| POST   | `/api/recipes` | Add a new recipe |
| PUT    | `/api/recipes/{id}` | Update a recipe |
| DELETE | `/api/recipes/{id}` | Delete a recipe |
| POST   | `/api/auth/register` | User registration |
| POST   | `/api/auth/login` | User login |

---

## 🔹 Deployment Instructions
(Add deployment steps for **Azure**, **AWS**, or other platforms if applicable)

---

## 📌 Contributing
Feel free to submit **issues** and **pull requests** to improve the project.

## 📌 License
This project is licensed under the **MIT License**.

---

## ✅ Final Steps
Once you’ve updated the README, add and push it to GitHub:
```sh
git add README.md
git commit -m "Updated README for full project"
git push origin main
```
