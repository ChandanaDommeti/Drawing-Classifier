# 🖌 Drawing Classifier  

A simple **machine learning** project that allows users to draw images on a **Tkinter GUI** and classify them into three different categories using various ML algorithms such as **SVM, KNN, Decision Trees, Random Forest, Naïve Bayes, and Logistic Regression**.  

## 🚀 Features  
- **Hand-drawn Image Classification** using ML models.  
- **Tkinter GUI** for drawing and interaction.  
- Supports multiple **ML models** with an easy switch option.  
- **Save & Load** trained models for future use.  
- **Project Saving** for continuing work later.  

## 📂 Project Structure  
```
📁 Drawing-Classifier  
 ├── 📄 drawing_classifier.py  # Main Python file  
 ├── 📁 Saved_Models/          # Directory to save trained models  
 ├── 📁 Class_Datasets/        # Stores user-created class images  
 ├── 📄 README.md              # Project Documentation  
 ├── 📄 requirements.txt       # Dependencies  
```

## 🛠 Installation  
### 1️⃣ Install Dependencies  
Make sure you have **Python 3.x** installed. Then, install the required libraries using:  
```bash
pip install numpy opencv-python scikit-learn pillow tkinter
```

### 2️⃣ Run the Application  
Simply execute the script using:  
```bash
python drawing_classifier.py
```

## 🎨 How It Works  
1. **Enter Class Names** – Define three categories for your classifier.  
2. **Draw Images** – Use the GUI to draw images and save them under the respective class.  
3. **Train Model** – Click the "Train Model" button to train the classifier.  
4. **Predict Drawings** – Draw and predict what category the sketch belongs to.  
5. **Change Model** – Rotate between different ML models for better results.  
6. **Save & Load** – Save your work and trained model for future use.  

## 🖥️ Supported Machine Learning Models  
- **Support Vector Machine (SVM) – Default**  
- **K-Nearest Neighbors (KNN)**  
- **Logistic Regression**  
- **Decision Tree**  
- **Random Forest**  
- **Naïve Bayes**  

## 📝 To-Do List  
✅ Basic drawing & classification functionality  
✅ Save and load models  
✅ Model selection feature  
⬜️ Improve accuracy with data augmentation  
⬜️ Add deep learning models (CNN) for better accuracy  

## 🤝 Contributing  
Feel free to fork this repo, open an issue, or submit a pull request!  

## 📜 License  
This project is **open-source** under the **MIT License**.  
