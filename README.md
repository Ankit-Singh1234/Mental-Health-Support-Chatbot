# 🧠 Mental Health Support Chatbot 💬

A web-based chatbot built using **Streamlit**, **OpenAI GPT-3.5**, and **TextBlob** for sentiment analysis.  
This app helps users express their feelings and receive emotional support, suggestions, and helpful resources. 💚

---

## ✨ Features

- 🤖 **AI-Powered Responses** using OpenAI's GPT-3.5 Turbo
- 😌 **Sentiment Analysis** to understand user mood
- 💡 **Coping Strategies** based on user sentiment
- 📈 **Mood Tracking Chart** over the session
- 📚 **Mental Health Resources** in sidebar
- 🔒 **Data Privacy Disclaimer** included

---

## 🚀 How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Ankit-Singh1234/Mental-Health-Support-Chatbot.git
   ```

2. **Navigate to the folder**  
   ```bash
   cd Mental-Health-Support-Chatbot
   ```

3. **(Optional) Create a virtual environment**  
   ```bash
   python -m venv venv
   venv\Scripts\activate      # On Windows
   source venv/bin/activate     # On macOS/Linux
   ```

4. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

5. **Set your OpenAI API key**  
   Create a file at `.streamlit/secrets.toml` with the following content:  
   ```toml
   [default]
   OPENAI_API_KEY = "your_openai_api_key"
   ```

6. **Run the app**  
   ```bash
   streamlit run app.py
   ```

---

## 📁 Project Structure

- `app.py` – Main application script
- `requirements.txt` – List of dependencies
- `.streamlit/secrets.toml` – For storing API key securely (you need to create this)

---

## ⚠️ Disclaimer

This application is intended **only for supportive and educational purposes**.  
It is **not a substitute for professional mental health care**.  
If you are in crisis, please reach out to a mental health professional or call a local helpline.

---

## 📝 License

Licensed under the **MIT License**.

---

Made with ❤️ to promote mental well-being.
