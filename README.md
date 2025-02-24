# Arabic Handwritten Text Identification Using Local Feature Extraction Techniques

##  Overview
This project is part of the **ENCS5343 Computer Vision** course at **Birzeit University**. The aim is to implement and compare local feature extraction techniques for identifying handwritten Arabic text using **SIFT (Scale-Invariant Feature Transform)** and **ORB (Oriented FAST and Rotated BRIEF)**. The study evaluates these algorithms based on accuracy, computational efficiency, and robustness.

##  Dataset
We use the **AHAWP dataset** (Arabic Handwritten Automatic Word Processing), which consists of **8,144 handwritten word images** from **82 different writers**. Each writer contributed **10 samples** for each of the **10 unique Arabic words**.

🔗 **Dataset Link**: [AHAWP Dataset](https://data.mendeley.com/datasets/2h76672znt/1/files/9031138a-b812-433e-a704-8acb1707936e)

##  Objectives
- **Extract features** using SIFT and ORB algorithms.
- **Transform features** into fixed-length histograms using the Bag of Words (BoW) model.
- **Train a classifier** using Support Vector Machines (SVM).
- **Evaluate performance** based on accuracy, robustness, and execution time.

## 🛠️ Methodology
### **Feature Extraction**
- **SIFT**: Detects and computes image key points and descriptors that are invariant to scale, rotation, and illumination.
- **ORB**: A computationally efficient alternative combining FAST key point detection and BRIEF descriptors.

### **Feature Representation**
- The **Bag of Words (BoW) model** transforms extracted features into fixed-length histograms.
- These histograms are used as input to train a **Support Vector Machine (SVM)** classifier.

### **Training and Classification**
- **SVM Classifier** is trained using BoW histograms.
- Hyperparameter tuning was performed to optimize kernel functions, regularization parameters, and gamma values.

## 📊 Results & Evaluation
The following metrics were used to compare **SIFT** and **ORB**:
1. **Accuracy** – Percentage of correctly classified samples.
2. **Execution Time** – Time taken for feature extraction and matching.
3. **Robustness** – Performance under variations in scale, rotation, illumination, and noise.
4. **Number of Key Points** – Comparison of detected key points.


## 🚀 Installation & Usage
1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/Arabic-Handwriting-Feature-Extraction.git
   cd Arabic-Handwriting-Feature-Extraction
