```markdown
# 📝 Todo App (Django + Docker)

A simple Todo wesite application built using **Django**, containerized with **Docker**, and orchestrated using **Docker Compose**. This project demonstrates end-to-end containerization, deployment, and image publishing to Docker Hub.

---

## 🚀 Features
- User authentication (Login / Register)
- Create, update, and delete tasks
- Simple and clean UI
- Containerized using Docker
- Multi-container setup using Docker Compose

---

## 🖼️ Application Preview

![Todo App Screenshot](./assets/todo-app.png)

> Make sure to save your screenshot as `todo-app.png` inside an `assets/` folder in your repo.

---

## 🛠️ Tech Stack
- **Backend:** Django (Python)
- **Containerization:** Docker
- **Orchestration:** Docker Compose
- **Version Control:** Git & GitHub
- **Image Hosting:** Docker Hub

---

## 📦 Project Structure
```

.
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── manage.py
├── app/
├── templates/
└── assets/
└── todo-app.png

````

---

## ⚙️ Setup & Run Locally

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
cd YOUR_REPO
````

### 2️⃣ Build and run using Docker Compose

```bash
docker-compose up --build
```

### 3️⃣ Access the application

```
http://localhost:2003
```

---

## 🐳 Docker Commands (Optional)

### Build Docker image

```bash
docker build -t todo-app .
```

### Run container

```bash
docker run -p 2003:2003 todo-app
```

---

## 📤 Docker Hub

Image pushed to Docker Hub:

```bash
docker pull vikas2128/todo-app:1.0
```

---

## 📚 What I Learned

* Writing Dockerfiles for Django applications
* Managing multi-container setups using Docker Compose
* Building and pushing Docker images to Docker Hub
* Running containerized applications locally

---

## 📌 Future Improvements

* Add database container (PostgreSQL)
* Deploy on AWS EC2
* Add CI/CD pipeline using Jenkins or GitHub Actions

---

## 👨‍💻 Author

**Vikas Angadi**

* GitHub: https://github.com/VikasAngadi1
* LinkedIn: https://linkedin.com/in/vikas-angadi

---

```
```
