# 👗 Fashion Recommender System

An AI-powered Fashion Recommender System that recommends visually similar fashion products based on an uploaded image. The application uses **ResNet50** for feature extraction and **Streamlit** for an interactive web interface.

---

## 📌 Features

- 📸 Upload an image of a fashion product
- 🤖 Extract deep image features using ResNet50
- 🔍 Find visually similar fashion items
- 🖥️ Interactive and user-friendly Streamlit interface
- ⚡ Fast image similarity search using precomputed feature vectors

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Streamlit**
- **NumPy**
- **Pandas**
- **OpenCV**
- **Pillow**
- **Scikit-learn**

---

## 📂 Project Structure

```text
Fashion-Recommender-System/
│
├── Dataset/
├── uploads/
├── featurevector.pkl
├── filenames.pkl
├── Feature Extraction.ipynb
├── main.py
├── requirements.txt
└── README.md
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/YourGitHubUsername/Fashion-Recommender-System.git
```

### 2. Navigate to the project

```bash
cd Fashion-Recommender-System
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
streamlit run main.py
```

---

## 🧠 How It Works

1. User uploads a fashion image.
2. ResNet50 extracts deep visual features.
3. Feature vectors are compared with the dataset.
4. The most similar fashion products are retrieved.
5. Recommended images are displayed in the Streamlit application.

---

## 📷 Screenshots

### Home Page

_Add your screenshot here_

### Recommendation Results

_Add your screenshot here_

---

## 📦 Dependencies

- Streamlit
- TensorFlow
- Keras
- NumPy
- Pandas
- OpenCV
- Pillow
- Scikit-learn

---

## 👩‍💻 Author

**Bhumi Bhosale**

- GitHub: https://github.com/BhumiBhosale
- LinkedIn: https://www.linkedin.com/in/bhumibhosale290705

---

## ⭐ If you found this project helpful

Please consider giving this repository a **Star ⭐**.
