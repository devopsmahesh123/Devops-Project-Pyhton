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
docker run -dt --name pythonapp -p 80:5000 devopsmahesh123/python:latest
```

Visit `http://<your-ec2-public-ip>` and you’ll see your app live!
Results: 
<img width="842" height="260" alt="image" src="https://github.com/user-attachments/assets/85e3ada6-af1b-4b06-bc1b-00422223220b" />
