## 🐳 Docker Commands

### ✅ Build and Tag
```bash
docker build -t sadeeq/devops-python-app:latest .
```

### 🔐 Login and Push
```bash
docker login
docker push sadeeq/devops-python-app:latest
```

---

## ☁️ Deploy on EC2

Once your EC2 instance is ready and Docker is installed:

```bash
docker pull sadeeq/devops-python-app:latest
docker run -d -p 80:5000 sadeeq/devops-python-app:latest
```

Visit `http://<your-ec2-public-ip>` and you’ll see your app live!
