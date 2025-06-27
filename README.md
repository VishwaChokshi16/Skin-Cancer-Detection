# 🩺 Skin Cancer Detection
A deep learning-based web application that predicts the most probable skin cancer diagnoses from dermatoscopic images. Users can upload an image and receive the top three likely conditions along with confidence scores.

## 📖 Overview
Skin cancer is one of the most common cancers globally. Early detection significantly improves treatment success. This project leverages computer vision and transfer learning to classify dermatoscopic images into multiple categories with high accuracy. This project aims to assist in early detection of skin cancer by classifying skin lesions as either benign (non-cancerous) or malignant (cancerous) using image-based prediction.

## ⚙️ Features
- Upload dermatoscopic images of skin lesions
- Returns top-3 predictions with probability scores
- Streamlined and intuitive UI
- Supports efficient batch processing and inference


## 🛠️ Tech Stack
| Layer       | Technology / Library              |
|-------------|-----------------------------------|
| Language    | Python 3.8+                       |
| ML Framework| TensorFlow / Keras                |
| Model       | Sequential                        |
| Dataset     | HAM10000 (Kaggle / ISIC Archive)  |
| Frontend    | HTML, CSS                         |
| Backend     | Flask                             |


## 🚀 Installation

### 1. Clone the repository
```bash
git clone https://github.com/VishwaChokshi16/Skin-Cancer-Detection.git
cd Skin-Cancer-Detection
```

### 2. Create and activate a virtual environment
```bash
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Usage
Start the Web App
```bash
python app.py
```
Visit http://localhost:5000 in your browser and upload a dermatoscopic image to get predictions. 


### 5. Download and place dataset
Download the HAM10000 Dataset and place it under the data/ directory.
