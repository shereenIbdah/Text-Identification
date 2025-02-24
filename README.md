# Arabic Handwritten Text Identification Using Local Feature Extraction Techniques

## 📌 Overview
This project is part of the **ENCS5343 Computer Vision** course at **Birzeit University**. The goal is to implement and compare **local feature extraction** techniques, specifically **SIFT (Scale-Invariant Feature Transform)** and **SURF (Speeded-Up Robust Features)**, for identifying handwritten Arabic text.

We use the **AHAWP dataset** (Arabic Handwritten Automatic Word Processing) to evaluate these algorithms based on accuracy, efficiency, and robustness.

## 📂 Dataset
We use the **AHAWP dataset**, which consists of **8,144 handwritten word images** from **82 different writers**. Each writer contributed **10 samples** for each of the **10 unique Arabic words**.

🔗 **Dataset Link**: [AHAWP Dataset](https://data.mendeley.com/datasets/2h76672znt/1/files/9031138a-b812-433e-a704-8acb1707936e)

## 🏆 Objectives
- **Preprocess** input data for better feature extraction.
- **Extract local features** using SIFT and SURF.
- **Match key points** between handwritten text images.
- **Evaluate performance** based on multiple metrics.

## 📊 Evaluation Metrics
We compare the **SIFT** and **SURF** algorithms using the following metrics:
1. **Accuracy** – Percentage of correctly matched key points.
2. **Time Efficiency** – Execution time for feature extraction and matching.
3. **Robustness** – Performance under scale, rotation, illumination, and noise variations.
4. **Number of Key Points** – Comparing detected key points for each algorithm.

## 🛠️ Installation & Setup
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Arabic-Handwriting-Feature-Extraction.git
   cd Arabic-Handwriting-Feature-Extraction
