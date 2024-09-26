# AI-Powered Translator Web App with Flask and Azure

**Short Description**:  
This AI Translator Web App is a real-time language translation tool built using Python, Flask, and Azure Cognitive Services' Translator API. The app enables users to translate text between multiple languages instantly, making communication across different languages easier and more accessible.

---

## Table of Contents
- [About](#about)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Folder Structure](#folder-structure)
- [Built With](#built-with)
- [License](#license)

---

## About
This web application leverages Flask as the backend framework and Azure Cognitive Services' Translator API for real-time language translation. Users can input text, choose the target language, and receive an instant translation, making this app ideal for multilingual communication.

---

## Features
- Real-time text translation
- Supports multiple languages
- Simple and intuitive UI
- Integrated with Azure Cognitive Services' Translator API

---

## Prerequisites
Before you begin, ensure you have the following installed:
- Python 3.8+
- Azure Subscription (for Translator API)
- Flask

You will also need an API key for the Translator service from Azure.

---

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/ai-translator-web-app.git
   cd ai-translator-web-app
   ```

2. **Set up a virtual environment** (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up environment variables**:
   Create a `.env` file in the project directory with the following:
   ```
   KEY=your_key
   ENDPOINT=your_endpoint
   LOCATION=your_location
   ```

5. **Run the Flask app**:
   ```bash
   python -m flask run
   ```
   The app will be available at `http://127.0.0.1:5000/`.

---

## Usage

1. Open the app in your browser by visiting `http://127.0.0.1:5000/`.
2. Enter the text you want to translate in the form.
3. Select the language you want to translate to from the dropdown menu.
4. Click "Translate" to get the translated text instantly.

---

## Folder Structure
```
.
├── app.py               # Flask application
├── templates            # Contains HTML files
│   ├── index.html       # Main page for input
│   └── results.html     # Displays the translated results
├── .env                 # Environment variables file
├── requirements.txt     # Dependencies
└── README.md            # Project README
```

---

## Built With
- **Python 3.8+**
- **Flask** - Lightweight WSGI web application framework
- **Azure Cognitive Services' Translator API** - Real-time translation service

---

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
