🌱 Crop Recommendation System
A machine learning–based web application that recommends the most suitable crop to grow based on soil and environmental conditions. Additionally, it provides detailed crop information including growth stages, fertilizer usage, and ideal conditions.

🚀 Features
🌾 Crop Prediction using trained ML model (based on N, P, K, temperature, humidity, pH, rainfall)

📖 Crop Information: View growth stages, soil types, and fertilizer recommendations

🔍 Search Crops by name and get instant insights

🧠 Smart UI with search filter and fruit-only toggle

👨‍🌾 Expert Contact Page for agricultural support

🧠 Machine Learning Model
Trained on dataset Crop_recommendation.csv

Inputs: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall

Tools: scikit-learn, LabelEncoder, StandardScaler

Output: Best crop recommendation from 22+ crop types

🗂 Project Structure
.
├── app.py                      # Main Flask backend
├── Crop_recommendation.csv    # Training dataset
├── crop_data.json             # Detailed crop info (growth, fertilizer, soil)
├── templates/
│   ├── about.html             # Crop browsing UI
│   ├── search.html            # Crop search page
│   └── contact.html           # Expert contacts
├── static/images/             # Crop images (named as <crop>.jpg)
├── model.pkl                  # Trained crop prediction model
├── scaler.pkl                 # Data scaler
├── label_encoder.pkl          # Crop label encoder
└── README.md
🌐 How It Works
User inputs environmental data

Backend sends data to ML model → predicts best crop

Returns result with:

Image

Growth stages

Fertilizer recommendation

Ideal soil type

🔧 Tech Stack
Layer	Tools Used
Frontend	HTML, CSS, JavaScript
Backend	Python, Flask
ML Model	scikit-learn, NumPy, Pickle
Data Format	CSV, JSON
🖼 Sample UI Pages
/about – Explore crops

/search – Search crops

/contact – Reach out to agri experts

✅ How to Run Locally
git clone <your-repo-url>
cd <project-folder>
pip install -r requirements.txt
python app.py
Then go to http://127.0.0.1:5000/ in your browser.

📜 License
This project is for educational and academic use.

