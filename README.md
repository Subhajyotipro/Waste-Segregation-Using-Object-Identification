# ♻️ Waste Segregation Using Object Identification

An AI-powered system to automatically detect and classify waste into  
**Recyclable**, **Organic**, and **Hazardous** categories using computer vision.

The project is designed for **real-world deployment** in **smart cities**, **public waste management**, and **mobile-based waste sorting systems**.

---

## 🧠 Core Model

- **Model:** YOLOv8 (Ultralytics)
- **Task:** Multi-class object detection
- **Classes:**
  - Recyclable
  - Organic
  - Hazardous
  - Contaminated-Recyclable (unique feature)
- **Framework:** PyTorch

---

## 1️⃣ Local Deployment (Laptop / Desktop)

### 📌 Use Case
- Model testing
- Dataset validation
- Demo for stakeholders

### 🛠️ Requirements
```bash
pip install ultralytics opencv-python torch
