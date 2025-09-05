ps## 🐳 Docker Commands

### ✅ Build and Tag
```bash
docker build -t devopsmahesh123/python:latest .
```

### 🔐 Login and Push
```bash
docker login
docker push devopsmahesh123/python:latest
```

---

## ☁️ Deploy on EC2

Once your EC2 instance is ready and Docker is installed:

```bash
docker pull devopsmahesh123/python:latest
docker run -d -p 80:5000 sadeeq/devops-python-app:latest
```

Visit `http://<your-ec2-public-ip>` and you’ll see your app live!
