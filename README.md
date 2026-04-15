🩺 HealthCare ChatBot
A simple yet intelligent AI-powered Disease Prediction Chatbot built with Python, scikit-learn, and pandas.

It analyzes your symptoms and helps predict possible diseases with precautions and useful information.

✨ Features
Natural Language Symptom Input – Describe your symptoms in plain English
Smart Symptom Extraction – Handles synonyms, typos, and fuzzy matching
Machine Learning Model – Trained using Random Forest Classifier
Interactive Guided Questions – Asks follow-up questions based on predicted disease
Severity & Duration Analysis
Precautions & Disease Description
Empathetic & Friendly Interface
🛠️ Tech Stack
Python 3
pandas & numpy
scikit-learn (RandomForestClassifier)
difflib (for fuzzy matching)
📁 Project Structure
HealthCare-ChatBot/
├── Data/
│   ├── Training.csv
│   └── Testing.csv
├── MasterData/
│   ├── symptom_Description.csv
│   ├── symptom_severity.csv
│   └── symptom_precaution.csv
├── main.py                 # Main chatbot script
├── README.md
└── requirements.txt

🚀 How to Run
1. Clone the repository
Bashgit clone https://github.com/yourusername/healthcare-chatbot.git
cd healthcare-chatbot
2. Install dependencies
Bashpip install -r requirements.txt
3. Run the chatbot
Bashpython main.py

📋 Requirements
Create a file named requirements.txt with the following content:
txtpandas
numpy
scikit-learn

🎯 How It Works

You describe your symptoms in a sentence
The bot intelligently extracts symptoms (even with typos or synonyms)
It makes an initial prediction using the trained model
Then asks targeted follow-up questions related to the suspected disease
Shows the final predicted disease with:
Confidence percentage
Disease description
Suggested precautions
A motivational health quote ❤️



🤖 Sample Interaction
text👉 Describe your symptoms: I have high fever and stomach pain
✅ Detected symptoms: fever, stomach_pain

👉 For how many days have you had these symptoms? : 3
👉 On a scale of 1–10, how severe do you feel? : 7

🤔 Let me ask you some more questions related to Viral Fever
👉 Do you also have chills? (yes/no): yes

---------------- Result ----------------
🩺 Based on your answers, you may have **Viral Fever**
🔎 Confidence: 92.45%
📖 About: Viral fever is a common illness caused by a virus...

🛡️ Suggested precautions:
1. Take rest and drink plenty of fluids
2. ...

⚠️ Important Disclaimer
This project is for educational purposes only.
It is not a substitute for professional medical advice, diagnosis, or treatment.
Always consult a qualified healthcare provider for any medical concerns.

🙌 Contributing
Feel free to fork this project and improve it!
Suggestions for better symptom extraction, adding more diseases, or improving the UI are always welcome.

💖 Made with Care
Built with ❤️ for learning and awareness.

Stay Healthy | Stay Safe 
text
