# 📸 Filtering Instagram Hashtags Through Crowdtagging and the HITS Algorithm

## 📖 Overview
This project focuses on filtering irrelevant hashtags on Instagram using the **HITS Algorithm** and a **Convolutional Neural Network (CNN)**.  
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

## 📦 Requirements
The project requires the following Python libraries:

- tensorflow  
- numpy  
- pandas  
- networkx  
- opencv-python  
- pillow  
- matplotlib  

Install dependencies using:

```
pip install -r requirements.txt
```

---

## 📂 Project Structure
```
project
│
├── Hashtag.py
├── RCNN.py
├── build_vocab.py
├── csv2imageGraphs.py
├── read_csv.py
├── write_bipartite.py
├── test.py
├── run.bat
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
git clone https://github.com/Saiharithaveluru2005/Filtering-Instagram-Hashtags-Through-Crowdtagging-and-the-HITS-Algorithm.git
```

Go to the project folder:

```
cd Filtering-Instagram-Hashtags-Through-Crowdtagging-and-the-HITS-Algorithm
```

Install required libraries:

```
pip install -r requirements.txt
```

---

## ▶️ Run the Project

```
python test.py
```

Or run using the batch file:

```
run.bat
```

---

## 📊 Dataset
This project uses image graph files and hashtag data for training and evaluation.

⚠️ Dataset is not included in this repository due to size limitations.

Please add the dataset files to the appropriate project directory before running the project.

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
