# 🛡️ SentinAI | Advanced Deepfake Detection System

A research-grade deep learning framework designed to detect high-fidelity AI-generated images using spatial, attentional, and graph-based structural verification.



## 📖 About
SentinAI tackles the growing challenge of hyper-realistic synthetic media by introducing a novel neural architecture: the **Tri-Stream Spatial-Graph-Attention Network (TSGA-Net)**. Trained extensively on a diverse dataset of 100,000+ real and synthetic images (from Stable Diffusion, Midjourney, and StyleGAN), the system moves beyond basic pixel-level artifact detection. By analyzing images across three dimensions simultaneously—visual texture, attentional focus, and structural consistency—SentinAI achieves an impressive 95.4% validation accuracy, ensuring robust digital forensics and media integrity.

---

## 🏗️ System Architecture (TSGA-Net)
<img width="800" alt="tsga_net_architecture" src="https://github.com/user-attachments/assets/208ea76d-01b4-49f4-bbab-a432c2c84c81" />

---

## ✨ Key Features
* **Novel Tri-Stream Processing:** Integrates Convolutional Neural Networks (CNN), Self-Attention mechanisms, and Graph Attention Networks (GAT) into a single, unified pipeline.
* **Spatial Feature Extraction:** Utilizes a ResNet-18 backbone to extract high-frequency visual textures, noise inconsistencies, and lighting transitions.
* **Attentional Artifact Localization:** Deploys a Self-Attention module to automatically weigh and focus on artifact-prone regions (e.g., eyes, lips, hair boundaries).
* **Graph-Based Structural Verification:** Transforms image patches into a graph structure, using GATs to verify geometric consistency, symmetry, and anatomical correctness.
* **Interactive Forensics Dashboard:** A fully deployed Streamlit web interface featuring real-time anomaly sensitivity calibration and confidence scoring.

---

## 📸 Web Interface

| SentinAI Console & Analysis Settings | Deepfake Forensics Report |
| :---: | :---: |
| <img width="400" alt="console_main" src="https://github.com/user-attachments/assets/363e44f7-5d95-45cf-84ea-b21f75ec2a47" /> | <img width="400" alt="forensics_result" src="https://github.com/user-attachments/assets/24bcd00d-04fd-43bc-96fb-3a128a10dc18" />|

---

## 💻 Tech Stack
* **Deep Learning Framework:** PyTorch
* **Graph Neural Networks:** PyTorch Geometric
* **Frontend & Deployment:** Streamlit
* **Data Processing:** pandas, NumPy, OpenCV
* **Hardware Utilization:** NVIDIA Tesla T4 GPUs (Training)

---

## 👥 Project Team
* **Vinod.N** - Team Leader & AI Architect
* **Rudra Pratap Singh** - Core Research Member
* **Prince Kumar Singh** - Core Research Member

---

## ©️ Copyright & Notice
**SentinAI is based on original research and architectural design conducted by Vinod.N and team.**

> **Proprietary Showcase:** This repository serves as a high-level architectural showcase for our 5th-semester Data Science and Machine Learning project. To protect the intellectual property, proprietary TSGA-Net model weights, and custom training datasets, exact installation procedures, source environment variables, and execution scripts have been intentionally omitted.

This project is for educational and portfolio purposes. Unauthorized copying, modification, or distribution of this project's core logic is strictly prohibited.
