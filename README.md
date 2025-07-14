# 🐱🐶 Cats vs Dogs Classification using Support Vector Machine (SVM)

This project is developed as **Task 3** of the **SkillCraft Technology Internship Program**. The goal is to classify images of cats and dogs using a **Support Vector Machine (SVM)** model based on extracted image features.

---

## 📌 Project Objective

The primary aim is to build an effective machine learning model that can differentiate between images of cats and dogs using a classical ML approach (SVM), rather than deep learning. This provides a strong understanding of image preprocessing and feature-based classification.

---

## 🗃️ Dataset Used

- **Name:** Dogs vs Cats  
- **Source:** Kaggle  
- **Link:** (https://www.kaggle.com/datasets/salader/dogs-vs-cats)

This dataset contains 25,000 labeled images of cats and dogs, with equal distribution across both classes.

---

## 🧠 Technologies and Libraries Used

- **Google Colab**
- **OpenCV** – for image reading and resizing  
- **NumPy** – for array operations  
- **scikit-learn** – for SVM modeling and evaluation  
- **Matplotlib** – for visualization

---

## 🔧 Steps to Use the Dataset Automatically

### 1. Get Your Kaggle API Token (`kaggle.json`)
- Visit your Kaggle account page: [https://www.kaggle.com/account](https://www.kaggle.com/account)
- Click on **"Create New API Token"** in the API section
- A file named `kaggle.json` will be downloaded

### 2. Upload `kaggle.json` to Google Colab
- Use the file upload option in Colab to upload your `kaggle.json` file

### 3. Set Up Kaggle Access in Colab
- Place the uploaded token in the correct path (`~/.kaggle/`)
- Set the appropriate file permissions
- Once set up, you can download any dataset directly from Kaggle using the CLI

### 4. Automatically Download and Unzip the Dataset
- Use Colab commands to download the dataset and unzip it into a working directory
- No manual downloads are required after `kaggle.json` setup

---

## ⚙️ Project Workflow

1. **Dataset Access:** Downloaded directly from Kaggle using the API token  
2. **Image Preprocessing:** Images are resized to a fixed size (e.g., 64x64) and flattened into vectors  
3. **Labeling:**  
   - Cats → Label `0`  
   - Dogs → Label `1`  
4. **Data Splitting:** The dataset is split into training and testing sets (e.g., 80/20)  
5. **Model Training:** A Support Vector Machine (SVM) is trained using the processed features  
6. **Evaluation:** Model performance is assessed using accuracy score and classification report  
7. **Visualization:** Sample predictions are displayed alongside the original images to visually validate predictions

---

## 📊 Learning Outcomes

- Understanding classical ML techniques in computer vision tasks  
- Working with real-world image datasets  
- Handling image preprocessing manually  
- Using SVM for binary image classification  
- Automating dataset access through Kaggle API

---

## ✅ Internship Tag

**Task Name:** SCT_ML_3  
**Internship:** SkillCraft Technology Internship Program  
**Domain:** Machine Learning  
**Topic:** Image Classification using SVM

---

## 🤝 Credits

- Dataset: Kaggle (Dogs vs Cats)  
- Internship Provider: SkillCraft Technology  
- Tools Used: Google Colab, OpenCV, scikit-learn

