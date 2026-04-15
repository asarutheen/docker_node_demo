# 🚀 Docker Node Demo

Simple Node.js app running inside Docker.

## 📦 Prerequisites

- Install Docker Desktop

## ▶️ Run the app

### 1. Clone repo

git clone https://github.com/asarutheen/docker_node_demo.git

cd docker-node-demo

### 2. Build Docker image

docker build -t docker-node-demo .

### 3. Run container

docker run -p 3000:3000 docker-node-demo

## 🌐 Access

http://localhost:3000

## 🧠 What this shows

- No need to install Node.js locally
- App runs inside container
- Same environment everywhere
