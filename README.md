# ♻️ Waste Segregation Using Object Identification

An AI-powered system to automatically detect and classify waste into categories using computer vision.

The project is designed for **real-world deployment** in **smart cities**, **public waste management**, and **mobile-based waste sorting systems**.

---

## 🧠 Core Model

- **Model:** Resnet 50 + Fine tuning
- **Task:** Multi-class object detection
- **Classes:**
  - Glass
  - cardboard
  - Paper
  - Plastic
  - Trash
  - Metal
  
- **Framework:** Keras / Tensor FLow

---

## 1️⃣ Local Deployment (Laptop / Desktop)

### 📌 Use Case
- Model testing
- Dataset validation
- Demo for stakeholders

### 🛠️ Requirements
```bash
FOR Dataset : 
# Download latest version
path = kagglehub.dataset_download("farzadnekouei/trash-type-image-dataset")
