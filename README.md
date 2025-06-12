🌾 Crop Recommendation System


A smart web-based application that recommends the best crop to grow based on soil and weather conditions using machine learning, and provides detailed crop insights for farmers, students, and researchers.


📸 Screenshots

🔮 Crop Prediction


![WhatsApp Image 2025-04-07 at 21 42 28_85998976](https://github.com/user-attachments/assets/ad3b3cbf-be36-4a2e-ac9d-d3026a27714f)



![WhatsApp Image 2025-04-07 at 21 58 31_124846ac](https://github.com/user-attachments/assets/ad615a53-109c-4760-9176-a5c567f74a37)



  🌱 Crop Info Search


  ![WhatsApp Image 2025-04-07 at 21 44 13_56b22d2d](https://github.com/user-attachments/assets/c8e0e218-dbf6-4591-ab66-7a22dfde3f64)



✅ Features


✅ Predicts the best crop based on:



Nitrogen, Phosphorus, Potassium



Temperature, Humidity, pH, Rainfall

📚 Crop details: Growth stages, fertilizers, soil type

🔎 Search crop info by name

🌐 Clean, responsive interface

🧑‍🌾 Contact agricultural experts directly


🧠 Machine Learning Model

Dataset: Crop_recommendation.csv

Algorithm: Trained model using Scikit-learn

Preprocessing: Normalized via StandardScaler, labels encoded with LabelEncoder

Input: N, P, K, Temperature, Humidity, pH, Rainfall

Output: Most suitable crop


🔧 Tech Stack

Layer	Tools Used

Frontend-	HTML, CSS, JavaScript

Backend-	Python, Flask

ML Model-	scikit-learn, NumPy, Pickle

Data Format-	CSV, JSON


🚀 Getting Started Locally


Clone the repo

git clone https://github.com/yourusername/crop-recommendation.git

cd crop-recommendation


Install dependencies

pip install -r requirements.txt


Run the Flask app



python app.py


Open in browser:

Go to http://127.0.0.1:5000/


🌍 Deployment Instructions


You can deploy this app on platforms like Render, Heroku, or Vercel (with Flask serverless).


🔹 For Render:

Create a render.yaml and add build + run commands


Add environment: Python 3.x

Upload your project and deploy

heroku login


heroku create crop-predictor


git push heroku main


Add:

requirements.txt

Procfile with: web: python app.py

🤝 Contributing


Want to add more crops, improve the UI, or optimize the model?

Feel free to fork this repo, open issues, and submit pull requests!

🪪 License

This project is intended for academic and learning purposes.

