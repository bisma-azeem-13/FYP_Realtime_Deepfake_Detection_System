# FYP_Realtime_Deepfake_Detection_System

# 🎭 FauxFace – Real-Time Deepfake Detection System

*“Fighting deepfakes with deep learning.”*

## 📌 About the Project

Deepfakes are no longer science fiction — they’re a real threat to trust, privacy, and digital authenticity. **FauxFace** is my Final Year Project, a real-time web-based system designed to detect deepfake videos across **live streams and uploaded content**.

The system combines **state-of-the-art deep learning models** (CNN + LSTM + Ensemble Learning) with **real-time video streaming tech (WebRTC + Django Channels)** to flag manipulated frames, generate confidence scores, and issue live alerts.

This repo is a portfolio showcase of my project journey — from early documentation to prototype building to the final submission.

⚠️ **Note:** The final source code is not shared here to protect project IP. Instead, you’ll find the **official documentation, final report, and presentation**.

---

## 🧠 Key Highlights

* 🔍 **Real-Time Detection:** Works on both live streaming & uploaded videos.
* 🖼 **Spatial + Temporal Analysis:** XceptionNet, InceptionResNetV2, ViT & 3D CNN ensemble.
* ⚡ **High Accuracy:** Achieved **95.31% validation accuracy** on FaceForensics++ dataset.
* 🔔 **Instant Alerts:** Detects and flags manipulated frames in milliseconds (\~52–90 FPS).
* 🔒 **Security First:** JWT/OAuth authentication, optional 2FA, and privacy-preserving design.
* 📊 **Visualization:** Detection results with frame-by-frame confidence scoring.

---

## 🧩 Tech Stack

* **Backend:** Django + Django Channels (WebSocket, WebRTC integration)
* **Frontend:** HTML, CSS, JavaScript
* **Deep Learning:** TensorFlow + Keras 
* **Computer Vision:** OpenCV
* **Development Tool:** Google Colab Pro+ (A100 GPU)

---

## 📂 Repo Contents

### 📄 Documentation Phase

* **System Requirements Specification (SRS)**
* **Design Document**

### 🧪 Prototype Phase

* TensorFlow-based deepfake detection prototype
* Experiments with CNN + temporal modeling + attention

### 🎓 Final Deliverables

* **📑 Final Report** (full system design, training, performance metrics, references)
* **📽️ Final Presentation Slides** (project demo + summary)

---

## 🚀 System Workflow

1. User logs in securely 
2. Provides input:

   * Upload a video **or**
   * Enable live stream via WebRTC
3. System extracts frames → runs through ensemble detection models
4. Flags manipulated content with **real-time alerts + confidence scores**
5. Users view results & can submit feedback to improve model reliability

---

## 🛠 Training Insights

* **Dataset:** FaceForensics++
* **Accuracy:** 95.31% (validation)
* **Latency:** \~11ms per step (real-time ready)
* **Batch Size:** 4 (optimized for GPU)

---

## 📥 Access the Project

* 📚 Documentation Phase(https://github.com/bisma-azeem-13/FYP_Documentation_Phase) 
* 📑 Prototype Phase(https://github.com/bisma-azeem-13/FYP_Prototype_Phase)
* 📽️ Final Phase (https://github.com/bisma-azeem-13/FYP_Realtime_Deepfake_Detection_System) | Video Demo (https://drive.google.com/file/d/1YpzPYFCUkOV6V_cOijYWRMNxCKOszLk_/view?usp=sharing)


---

## 💬 Connect with Me

Let’s talk **AI, deepfakes, and machine learning research** — or if you’re stuck on your own FYP, I’d be happy to share tips!

💼 If you’re a company, researcher, or professional interested in:

* discussing this project in detail,
* exploring collaboration,
* or acquiring access to the **codebase / system**,

👉 feel free to reach out directly:

* 🌐 [LinkedIn](https://www.linkedin.com/in/bisma-azeem-qureshi/)
* 📧 **[bismazeem1304@gmail.com]**

---

✨ *“Innovation means solving real problems — I built FauxFace to protect digital trust, and I’d love to see it make an impact beyond the classroom.”*


