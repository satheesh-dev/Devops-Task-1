# DevOps Task 1 – CI/CD Pipeline with GitHub Actions & Docker

This project is a demonstration of a basic CI/CD pipeline using **GitHub Actions** and **DockerHub**. It includes a simple Node.js web server and automates the testing, building, and deployment of the app as a Docker image.

---

## 🔧 Project Structure

- `index.js` – A basic HTTP server with a custom message.
- `Dockerfile` – Used to containerize the application.
- `.github/workflows/main.yml` – GitHub Actions CI/CD pipeline configuration.

---

## 🚀 Features Implemented

✅ Simple Node.js server  
✅ Dockerfile for containerization  
✅ GitHub repo with workflow automation  
✅ Automated build/test on push  
✅ Docker image pushed to DockerHub  
✅ Local Docker run and verification  

---

## ⚙️ CI/CD Workflow

The pipeline is triggered on every push to the `main` branch:

1. **Checkout Code**  
2. **Set up Node.js**  
3. **Install Dependencies**  
4. **Run Tests**  
5. **Build Docker Image**  
6. **Push Image to DockerHub**

---

## 🐳 DockerHub

Image is available at:  
🔗 [https://hub.docker.com/r/satheesh2003/devops-task-1](https://hub.docker.com/r/satheesh2003/devops-task-1)

To pull and run the image:

```bash
docker pull satheesh2003/devops-task-1:latest
docker run -p 3000:3000 satheesh2003/devops-task-1:latest

Then open: http://localhost:3000

<img width="1913" height="913" alt="Screenshot 2025-08-04 195338" src="https://github.com/user-attachments/assets/97d49284-e892-4d27-b082-98cb8d7b7abc" />

