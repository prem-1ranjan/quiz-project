# 🚀 Quiz Application (Full Stack Project)

This is a full-stack Quiz Application built using:

* 🎨 **Frontend**: HTML, CSS, JavaScript
* ⚙️ **Backend**: Spring Boot (Java)
* 🗄️ **Database**: MySQL

---

## 📂 Project Structure

```
quiz-project/
 ├── frontend/   # UI (HTML, CSS, JS)
 └── backend/    # Spring Boot API
```

---

## ✨ Features

* 🧠 Attempt quizzes
* 📊 Instant result calculation
* 🏆 Top performers section
* 🔗 Frontend connected with backend APIs
* 💾 Data stored in MySQL

---

## 🛠️ Setup Instructions

### 🔹 1. Clone the Repository

```
git clone https://github.com/your-username/quiz-project.git
cd quiz-project
```

---

### 🔹 2. Backend Setup (Spring Boot)

1. Open `backend` folder in IntelliJ
2. Configure MySQL in `application.properties`

Example:

```
spring.datasource.url=jdbc:mysql://localhost:3306/quizdb
spring.datasource.username=root
spring.datasource.password=your_password
```

3. Run the Spring Boot application

---

### 🔹 3. Frontend Setup

1. Open `frontend` folder in VS Code
2. Run using Live Server or open `index.html`

---

## 🗄️ Database Setup

* Create a database in MySQL:

```
CREATE DATABASE quizdb;
```

* Tables will be auto-created (if using JPA) or create manually

---

## 🌐 API Endpoints (Example)

* `GET /questions` → Fetch questions
* `POST /submit` → Submit quiz
* `GET /result` → Get result

---

## 📸 Screenshots

(Add your project screenshots here)

---

## 🚀 Future Improvements

* Login & Authentication
* Timer-based quiz
* Leaderboard with real users
* Deploy on cloud (AWS / Render / Vercel)

---

## 👨‍💻 Author

**Prem Ranjan**

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!

