# Health Chatbot using Flask & Gemini AI

## Overview
This is a simple **Flask-based Health Chatbot** that uses Google's **Gemini AI** to provide responses to health-related questions. The chatbot is designed to answer queries about various health topics such as diseases, symptoms, treatments, nutrition, and fitness.

## Features
- Uses **Gemini AI (Generative Model)** for generating responses.
- Recognizes health-related questions using keyword filtering.
- **Flask Web App** for easy interaction.
- Supports **JSON-based API** for chatbot integration.

## Tech Stack
- **Python** (Flask)
- **Google Gemini AI** (Generative Model API)
- **HTML/CSS/JavaScript** (for frontend)

## Project Structure
```
/health-chatbot
│── app.py                 # Main Flask app
│── templates/
│   └── index.html         # Frontend UI
│── requirements.txt       # Python dependencies
│── README.md              # Project documentation
```

## Getting Started

### 🔹 1. Clone the repository
```sh
git clone https://github.com/jeslipriya/AI-Health-Chatbot.git
cd AI-Health-Chatbot
```

### 🔹 2. Create a virtual environment (optional but recommended)
```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate  # On Windows
```

### 🔹 3. Install dependencies
```sh
pip install -r requirements.txt
```

### 🔹 4. Set up API Key
Replace `API_KEY` in `app.py` with your actual **Google Gemini API Key**.

### 🔹 5. Run the Flask app
```sh
python app.py
```
Access the chatbot at **http://127.0.0.1:5000/** in your browser.

## API Endpoint
The chatbot also supports a **POST** request for API integration:
```
POST /ask
Request Body: { "question": "What are the symptoms of flu?" }
Response: { "answer": "Flu symptoms include fever, cough, sore throat..." }
```

## Customization
- Modify `HEALTH_KEYWORDS` in `app.py` to improve keyword filtering.
- Edit `index.html` for a better UI experience.

## Contributing
Pull requests are welcome! Feel free to suggest improvements.

---
**Let's build smarter health solutions together!**

