# 🤖 AI Chatbot with Voice & Smart Responses

An intelligent chatbot that understands and replies to user messages using **natural language processing**, and even responds with **realistic voice output**!

---

## 🧠 Features

- 💬 Context-aware smart chatbot  
- 🗣️ Voice replies powered by ElevenLabs Text-to-Speech  
- 🧠 Smart response generation using Cohere API  
- 🖥️ Simple and clean interface (Terminal or optional GUI)  

---

## 🛠️ Technologies Used

- **Python**  
- **Cohere API** – Generates human-like responses  
- **ElevenLabs API** – Converts text to speech  
- `requests`, `playsound`, `os`, `time` – Standard Python libraries  

---

## 🔐 API Keys

This project uses two external APIs:

- `COHERE_API_KEY` – For generating smart replies  
- `ELEVENLABS_API_KEY` – For voice output  


---

## 🚀 How to Run

1. Clone the repository
Bash ->
git clone https://github.com/your-username/ai-chatbot  
cd ai-chatbot  

2. Install dependencies
Bash ->
pip install -r requirements.txt  

3. Add your API keys

- Option 1: Create a .env file and paste your keys there.  
- Option 2: Insert them directly in the Python file (not recommended).  

4. Run the chatbot
Bass ->
python chatbot.py  

---

## 📦 Example Output

User: "Hi, how are you?"  
Chatbot: "I'm doing great! How can I assist you today?"  

🔊 Voice plays automatically using ElevenLabs...

---

## 🖼️ Screenshot

> 📸 Add your screenshot below for visual reference:

![Chatbot Screenshot](path/to/your/screenshot.png)

---

