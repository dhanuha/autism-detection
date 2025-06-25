# 🧠 Autism Spectrum Disorder Detection in Children Using Machine Learning

## 🔍 Overview

This project is part of a broader research initiative focused on the early detection of Autism Spectrum Disorder (ASD) in children aged two years and below, using eye-tracking data and machine learning. Conducted during my internship at **Polytech Tours, Université de Tours, France**, my primary contributions were centered on building the data processing pipeline and developing initial machine learning models. This work laid the foundation for later deep learning-based classification systems.

The objective was to minimize reliance on traditional clinical diagnostics by identifying visual attention markers through AI-driven pattern recognition.

---

## 👨‍💻 My Contributions

### 1. Data Preprocessing & Cleaning
- Processed and standardized over **4,000 multi-sheet eye-tracking records** from pediatric subjects.
- Performed extensive data cleaning:
  - Removed duplicate entries and irrelevant sheets.
  - Addressed missing values by marking "no data" instances.
  - Parsed metadata fields (e.g., filename, patient ID, look zones).
- Consolidated all patient data into a single, structured dataset suitable for ML workflows.

### 2. Heatmap Generation
- Transformed gaze coordinate data into **1024×768 resolution heatmaps** to visually represent attention density.
- Enhanced spatial visibility using **7×7 Gaussian filtering**.
- Organized output by image ID and classification label to support supervised model training.

### 3. Initial Model Prototyping
- Built and evaluated baseline **K-Nearest Neighbors (KNN)** and **Convolutional Neural Network (CNN)** classifiers using the generated heatmaps.
- Achieved ~70% accuracy on preliminary CNN trials, confirming the effectiveness of the data pipeline.

---

## 🛠️ Technologies & Tools

- **Languages:** Python  
- **Libraries:** pandas, NumPy, matplotlib, seaborn, TensorFlow, Keras  
- **Tools:** Jupyter Notebook, Anaconda  
- **Data Collection Tool:** FaceLab Eye-Tracking System (60Hz)  
- **Data Format:** Multi-sheet Excel files (per patient and image stimulus)

---

## 💡 Skills Gained

- **Data Wrangling & Cleaning:** Proficient in cleaning real-world biomedical datasets, handling null values, noisy records, and structural inconsistencies.
- **Data Visualization:** Created meaningful visual representations (heatmaps) from raw eye-tracking coordinates to identify behavioral patterns.
- **Image Processing:** Applied Gaussian filters to improve feature visibility for downstream computer vision tasks.
- **Machine Learning Foundations:** Gained practical experience with supervised learning, model training/testing, and baseline evaluation using KNN and CNN.
- **Deep Learning with TensorFlow/Keras:** Developed a working understanding of CNN architecture, activation functions, pooling layers, and model tuning.
- **Project Structuring & Workflow Automation:** Designed modular, reproducible data processing and modeling workflows for scalability.
- **Applied Research Experience:** Contributed to a real-world, interdisciplinary research project with applications in pediatric behavioral health diagnostics.

---

## Document
- access the detailed [project documentation](./autism-detection.pdf).
