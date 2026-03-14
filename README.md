# 📸 Filtering Instagram Hashtags Through Crowdtagging and the HITS Algorithm

## 📖 Overview
This project focuses on filtering irrelevant hashtags on :contentReference[oaicite:1]{index=1} using the **:contentReference[oaicite:2]{index=2}** and a **:contentReference[oaicite:3]{index=3} (CNN)**.  
The system analyzes crowd-generated hashtags and compares them with the actual image content to identify relevant tags and remove unrelated ones. This improves image search accuracy and creates cleaner datasets for automatic image annotation systems.

---

## ✨ Features
- 🔍 Detects relevant and irrelevant hashtags  
- 📊 Uses HITS Algorithm to rank annotators and hashtags  
- 🧠 Uses CNN to analyze image content  
- ⚡ Improves accuracy of image search and annotation  
- 🗂️ Helps build cleaner datasets for machine learning  

---

## 🛠️ Technologies Used
- Python  
- Deep Learning (CNN)  
- HITS Algorithm  
- TensorFlow / Keras  
- Image Processing  

---

## 📂 Project Structure
```
instagram-hashtag-filtering
│
├── dataset
│   ├── images
│   └── hashtags.csv
│
├── hits_algorithm
│   └── hits.py
│
├── cnn_model
│   └── image_classifier.py
│
├── app
│   └── main.py
│
├── requirements.txt
└── README.md
```

---

## ⚙️ How It Works
1. Upload an image.  
2. CNN analyzes the visual content of the image.  
3. Crowd-generated hashtags are evaluated using the HITS Algorithm.  
4. The system filters out irrelevant hashtags.  
5. Only relevant hashtags are retained.  

---

## 🚀 Installation

Clone the repository:

```
git clone https://github.com/your-username/instagram-hashtag-filtering.git
```

Go to the project folder:

```
cd instagram-hashtag-filtering
```

Install required libraries:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```
python app/main.py
```

---

## 🎯 Applications
- Automatic Image Annotation  
- Social Media Hashtag Filtering  
- Content-Based Image Retrieval  
- Image Dataset Cleaning  

---

## 👨‍💻 Author
Project developed for academic and research purposes.

---
