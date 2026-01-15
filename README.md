🚀 AI Vision: CIFAR-10 Image Classifier
A high-performance image classification system built on ResNet18 and fine-tuned to achieve 88% accuracy on the CIFAR-10 dataset. This project features a modern Glassmorphism web interface and a robust FastAPI backend, fully containerized and deployed for production.

## 🚀 Live Demo (Hosted on Render)

🔗 **Live Application URL:**  
👉 https://ai-image-classifier-10.onrender.com

🔗 **Docker:**  
👉 https://hub.docker.com/repository/docker/mohdmusheer/ai-image-classifier-10


🌟 Key Features
Deep Learning Engine: Powered by a ResNet18 architecture trained with PyTorch.

Interactive UI: Modern HTML5/Tailwind CSS frontend with an animated mesh gradient background.

Instant Prediction: Real-time inference with progress indicators.

Fully Containerized: Easy to deploy anywhere via Docker.

Cloud Hosted: Live API and Frontend.

The project includes:
- Deep Learning model (ResNet18)
- REST API using FastAPI
- Interactive frontend UI
- Dockerized deployment
- Live hosting on Render

---<Br>
Metric,Value<Br>
Architecture,ResNet18<Br>
Dataset,CIFAR-10<Br>
Accuracy,88.42%<Br>
Inference Time,~20ms (on CPU)<Br>
## 🔍 What This Model Can Detect

The model classifies images into the following categories:

- ✈️ Plane  
- 🚗 Car  
- 🐦 Bird  
- 🐱 Cat  
- 🦌 Deer  
- 🐶 Dog  
- 🐸 Frog  
- 🐴 Horse  
- 🚢 Ship  
- 🚚 Truck  

---

## 📊 Model Performance

| Metric | Value |
|------|------|
| Dataset | CIFAR-10 |
| Architecture | ResNet18 (Pretrained) |
| Framework | PyTorch |
| Test Accuracy | **~88%** |
| Loss Function | CrossEntropyLoss (Label Smoothing) |

---

## 🧠 Tech Stack

- **Python 3.10**
- **PyTorch & Torchvision**
- **FastAPI** (Backend / REST API)
- **HTML, CSS, JavaScript** (Frontend)
- **Docker** (Containerization)
- **Render** (Cloud Deployment)

---

## 🖼️ Web Interface Features

- Gradient animated background
- Image upload & preview
- “Load Sample Image” button
- Predict button with progress bar
- Displays prediction + confidence
- Responsive and clean UI

---



---

## 🐳 Docker Deployment

The entire application is containerized using Docker.

### 🔗 Docker Image
👉 https://hub.docker.com/r/your-docker-username/ai-vision-classifier

### ▶️ Run with Docker
```bash
docker pull your-docker-username/ai-vision-classifier
docker run -p 8000:8000 your-docker-username/ai-vision-classifier
