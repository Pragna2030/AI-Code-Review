# 🤖 AI Code Review System (Spring Boot Full Stack)

An AI-powered code review system built using Spring Boot that analyzes code for bugs, security vulnerabilities, and best practices. It provides real-time feedback, automated suggestions, and helps developers improve code quality efficiently.

---

## 🚀 Features

* 🔍 Automated Code Analysis
* 🧠 AI-based Suggestions & Improvements
* 🛡️ Security Vulnerability Detection
* ⚡ Real-time Feedback
* 📊 Code Quality Insights
* 🧩 Scalable Full Stack Architecture

---

## 🛠️ Tech Stack

### Backend

* Java
* Spring Boot
* Spring Data JPA
* Hibernate

### Frontend

* frontend tech: HTML-CSS-JS

### AI Integration

*  API used: OpenAI 

### Database

* MySQL / PostgreSQL

---

## 📂 Project Structure

```
src/
 ├── controller/
 ├── service/
 ├── repository/
 ├── model/
 └── config/
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/ai-code-review.git
cd ai-code-review
```

### 2. Configure Database

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/your_db
spring.datasource.username=root
spring.datasource.password=your_password
```

### 3. Run the Application

```bash
mvn spring-boot:run
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description            |
| ------ | -------- | ---------------------- |
| POST   | /review  | Submit code for review |
| GET    | /history | Get previous reviews   |

---

## 📸 How It Works

1. User submits code
2. Backend processes request
3. AI analyzes code
4. Suggestions & issues returned

---

## 🎯 Future Enhancements

* GitHub Integration
* Multi-language Support
* Advanced AI Models
* Code Auto-Fix Feature

---

## 📄 License

This project is licensed under the MIT License.

