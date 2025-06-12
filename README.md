
# 🌾 Crop Recommendation System

A smart web-based application that recommends the best crop to grow based on soil and weather conditions using machine learning, and provides detailed crop insights for farmers, students, and researchers.

---

## 📸 Screenshots

### 🔮 Crop Prediction
![WhatsApp Image 2025-04-07 at 21 42 28_76c80b1c](https://github.com/user-attachments/assets/d331056a-e073-40d8-b2b8-531a01ecc1ec)


### 🌱 Crop Info Search
![WhatsApp Image 2025-04-07 at 21 58 31_e6597b09](https://github.com/user-attachments/assets/8d2a284b-c6e6-412a-b317-25a67af01657)



### 📋 Crop Details
![WhatsApp Image 2025-04-07 at 21 44 13_9c2a4c68](https://github.com/user-attachments/assets/03b161df-6e9d-4521-aa3a-07e81ba82792)



---

## ✅ Features

- ✅ Predicts the best crop based on:
  - Nitrogen, Phosphorus, Potassium
  - Temperature, Humidity, pH, Rainfall
- 📚 Crop details: Growth stages, fertilizers, soil type
- 🔎 Search crop info by name
- 🌐 Clean, responsive interface
- 🧑‍🌾 Contact agricultural experts directly

---

## 🧠 Machine Learning Model

- **Dataset:** `Crop_recommendation.csv`
- **Algorithm:** Trained model using Scikit-learn
- **Preprocessing:** Normalized via `StandardScaler`, labels encoded with `LabelEncoder`
- **Input:** N, P, K, Temperature, Humidity, pH, Rainfall
- **Output:** Most suitable crop

---

## 🔧 Tech Stack

| Layer       | Tools Used                   |
|-------------|------------------------------|
| Frontend    | HTML, CSS, JavaScript        |
| Backend     | Python, Flask                |
| ML Model    | scikit-learn, NumPy, Pickle  |
| Data Format | CSV, JSON                    |

---

## 🚀 Getting Started Locally

1. **Clone the repo**

```bash
git clone https://github.com/yourusername/crop-recommendation.git
cd crop-recommendation
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the Flask app**

```bash
python app.py
```

4. Open in browser:  
Go to `http://127.0.0.1:5000/`

---

## 🌍 Deployment Instructions

You can deploy this app on platforms like **Render**, **Heroku**, or **Vercel (with Flask serverless)**.

### 🔹 For Render:
- Create a `render.yaml` and add build + run commands
- Add environment: Python 3.x
- Upload your project and deploy

### 🔹 For Heroku:
```bash
heroku login
heroku create crop-predictor
git push heroku main
```

Add:
- `requirements.txt`
- `Procfile` with: `web: python app.py`

---

## 🤝 Contributing

Want to add more crops, improve the UI, or optimize the model?  
Feel free to fork this repo, open issues, and submit pull requests!

---

## 🪪 License

This project is intended for academic and learning purposes.
