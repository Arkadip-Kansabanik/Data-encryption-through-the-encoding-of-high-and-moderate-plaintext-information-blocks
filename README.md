# 🔐 Image Encryption using Cryptography and Machine Learning

A hybrid Machine Learning and Cryptography based image encryption system for secure and efficient data protection using selective encryption, chaotic maps, and adaptive block classification.

---

# 📌 Project Overview

This project presents a fusion of **Machine Learning** and **Cryptography** to achieve fast and secure image encryption.  
The system intelligently classifies image blocks based on information density and selectively applies encryption techniques to optimize both:

- 🔒 Security
- ⚡ Computational Efficiency

The proposed approach is especially suitable for:

- IoT Systems
- Real-time Applications
- Cloud Security
- Edge Computing
- Resource-Constrained Devices

---

# ❗ Problem Statement

Traditional encryption algorithms encrypt all image data uniformly, which leads to:

- High computational complexity
- Increased encryption time
- Poor real-time performance
- Inefficiency for large image datasets

This project aims to solve these problems by:

- Identifying high-information image blocks using Machine Learning
- Applying stronger encryption only where necessary
- Reducing unnecessary encryption overhead
- Maintaining strong confidentiality and integrity

---

# 🧠 Proposed Solution

The system combines:

- Machine Learning based block classification
- Selective image encryption
- Bit-plane extraction
- Chaotic map based confusion and diffusion
- Multiple S-box substitution
- XOR based diffusion encryption

Only important image blocks are encrypted, reducing overall processing time while preserving security.

---

# 🏗️ System Architecture

```text
Input Image
      │
      ▼
Image Division into 8×8 Blocks
      │
      ▼
Feature Extraction
(Entropy, Energy, Contrast, Homogeneity)
      │
      ▼
K-Means Clustering
      │
      ▼
ML Classification
(HIB / MIB / LIB)
      │
      ▼
Selective Encryption
(Only HIB & MIB)
      │
      ▼
Bit Plane Extraction
      │
      ▼
Bit Plane Rotation
(90°, 180°, 270°)
      │
      ▼
Chaotic Sequence Generation
      │
      ▼
Permutation & Confusion
      │
      ▼
Multiple S-Box Substitution
      │
      ▼
Chaotic XOR Diffusion
      │
      ▼
Final Encrypted Image
```

---

# ⚙️ Features

- Adaptive encryption framework
- Selective encryption for faster processing
- Chaotic map based security
- Multiple S-box substitution
- Machine Learning driven optimization
- Real-time encryption suitability
- Reduced computational overhead

---

# 🛠️ Technologies & Tools Used

## Programming Language
- Python 3.7

## Libraries & Frameworks
- NumPy
- OpenCV
- Scikit-learn
- Matplotlib
- Pandas

## Platform
- Windows 11
- Intel i5 (11th Gen)
- 8GB RAM

---

# 🤖 Machine Learning Models Used

The following ML algorithms were used for block classification:

| Model | Purpose |
|---|---|
| K-Nearest Neighbors (KNN) | Block Classification |
| Decision Tree | Information Density Classification |
| Random Forest | Ensemble Classification |
| Support Vector Machine (SVM) | High Accuracy Classification |
| Naive Bayes | Probabilistic Classification |
| K-Means Clustering | Grouping Information Blocks |

---

# 📊 Feature Extraction Parameters

Each image block is analyzed using:

| Feature | Description |
|---|---|
| Entropy | Measures randomness |
| Energy | Measures uniformity |
| Contrast | Measures intensity variation |
| Homogeneity | Measures similarity between pixels |

---

# 🔐 Encryption Methodology

## 1️⃣ Image Division
The input image is divided into:

- 8×8 non-overlapping blocks

---

## 2️⃣ Feature Extraction
Features like entropy, energy, contrast, and homogeneity are computed for each block.

---

## 3️⃣ ML-Based Classification
Blocks are classified into:

- High Information Blocks (HIB)
- Moderate Information Blocks (MIB)
- Low Information Blocks (LIB)

Only HIB and MIB are encrypted.

---

## 4️⃣ Bit-Plane Extraction
Each selected block is split into 8 bit-planes.

Only higher significant bit-planes are encrypted.

---

## 5️⃣ Bit-Plane Rotation
Bit-planes are rotated at:

- 90°
- 180°
- 270°

to improve diffusion.

---

## 6️⃣ Chaotic Sequence Generation
Chaotic maps generate pseudo-random sequences for:

- Confusion
- Permutation
- Diffusion

---

## 7️⃣ Multiple S-Box Substitution
Pixel values are substituted using multiple S-boxes to increase randomness and security.

---

## 8️⃣ Chaotic XOR Diffusion
Final diffusion is performed using XOR with chaotic noisy images.

---

# 🔓 Decryption Process

Decryption reverses the encryption steps:

1. XOR Diffusion Reversal
2. Reverse S-box Substitution
3. Reverse Permutation
4. Reverse Rotation
5. Bit-plane Reconstruction

---

# 📈 Results

The proposed model achieved:

- Faster encryption compared to full-image encryption
- Reduced computational cost
- Strong resistance against attacks
- Better suitability for real-time applications
- Efficient selective encryption

## Key Achievements

✅ Reduced encryption time  
✅ Improved computational efficiency  
✅ Secure chaotic encryption  
✅ Intelligent ML-based adaptive encryption  
✅ Suitable for IoT environments  

---

# 📂 Project Structure

```bash
Image-Encryption-ML-Cryptography/
│
├── Image Encryption using Cryptography and Machine Learning.ipynb
├── Final_project.pdf
├── README.md
│
└── requirements.txt
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/Image-Encryption-ML-Cryptography.git
```

---

## 2️⃣ Navigate to Project Directory

```bash
cd Image-Encryption-ML-Cryptography
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Run the Notebook

```bash
jupyter notebook
```

Open:

```bash
Image Encryption using Cryptography and Machine Learning.ipynb
```

---

# 📦 Requirements

Example `requirements.txt`

```txt
numpy
opencv-python
scikit-learn
matplotlib
pandas
```

---

# 🚀 Future Improvements

- Deep Learning based adaptive encryption
- Quantum-resistant cryptography
- Real-time cloud deployment
- Explainable AI for encryption decisions
- Cross-platform optimization
- Adversarial attack resistance

---

# 🌍 Applications

- Secure IoT Communication
- Healthcare Data Protection
- Smart Cities
- Military Communication
- Cloud Security
- Mobile Devices
- Digital Banking

---

