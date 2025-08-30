# AI-Powered Assistant

## 📌 Overview
AI-Powered  Assistant is a Python-based **voice-controlled assistant** that integrates with **OpenAI’s GPT models** and **speech recognition** to simulate a smart personal assistant.  
It can take **voice commands**, **interact with AI for conversational responses**, and perform **actions like searching and playing YouTube videos**.

## 🚀 Features
- 🎙️ **Voice Recognition** – Understands voice commands using speech recognition.  
- 🤖 **Conversational AI** – Generates intelligent responses via OpenAI’s GPT model.  
- 🔊 **Text-to-Speech** – Speaks responses aloud using the system’s text-to-speech.  
- 🌐 **Web Automation** – Opens YouTube, performs searches, and plays videos.  
- 📂 **Response Logging** – Stores AI responses as text files for later reference.  

## 🛠️ Tech Stack
- **Python 3.8+**  
- **SpeechRecognition** – Voice input  
- **OpenAI API** – AI-generated responses  
- **OS & Webbrowser** – System commands and YouTube access  
- **Datetime, NumPy, Random** – Utility functions  

## ⚙️ Workflow
1. User speaks into the microphone.  
2. Speech is converted into text using `speech_recognition`.  
3. Assistant decides whether to **reply with AI** or **execute YouTube commands**.  
4. OpenAI GPT generates natural language responses.  
5. The system’s speech engine (`say`) reads the response aloud.  
6. All responses are logged into text files inside the `Openai/` folder.  

## 🛠️ Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/AI-Powered-Assistant.git
   cd AI-Powered-YouTube-Assistant
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Add your OpenAI API Key in config.py:

python
Copy code
apikey = "your-openai-api-key"
▶️ Run the Project
bash
Copy code
python main.py
🎯 Example Usage
User: “Play Alan Walker on YouTube.”
Assistant: Opens YouTube and plays the requested video.

User: “Tell me about Artificial Intelligence.”
Assistant: Responds with a detailed AI-generated explanation and speaks it aloud.

📂 Project Structure
bash
Copy code
AI-Powered-YouTube-Assistant/
│── main.py             # Entry point
│── config.py           # API key configuration
│── requirements.txt    # Dependencies
│── README.md           # Documentation
│── /Openai             # AI response logs (created dynamically)

