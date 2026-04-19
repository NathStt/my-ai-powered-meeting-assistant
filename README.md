# 🎙️ AI-Powered Meeting Assistant

An AI-powered voice assistant that converts speech to text, processes it using a language model, and extracts useful insights from conversations.

This project demonstrates a simple end-to-end pipeline combining:
- 🎧 Speech-to-Text (STT)
- 🧠 Large Language Models (LLM)
- 🔊 Audio processing

---

## 🚀 Features

- Convert audio → text using Speech-to-Text
- Analyze conversations using an LLM
- Extract key points from meetings
- Modular Python scripts for easy customization
- Ready to extend into real-time meeting assistant

---

## 🧱 Project Structure

```
my-ai-powered-meeting-assistant/
│
├── downloaded_audio.mp3      # Sample audio file
├── hello.py                 # Test / starter script
├── simple_llm.py            # LLM interaction logic
├── simple_speech2text.py    # Basic speech-to-text script
├── speech2text_app.py       # App-level STT integration
├── speech_analyzer.py       # Analyze and extract insights
├── requirements.txt         # Dependencies
└── README.md
```

---

## ⚙️ Installation

### 1. Clone the repository
```bash
git clone https://github.com/NathStt/my-ai-powered-meeting-assistant.git
cd my-ai-powered-meeting-assistant
```

### 2. (Optional) Create a virtual environment
```bash
python3 -m venv my_env
source my_env/bin/activate   # Mac/Linux
# my_env\Scripts\activate    # Windows
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Setup

Depending on your implementation, you may need API keys:

### OpenAI
```bash
export OPENAI_API_KEY="your_api_key"
```

### IBM Watson
```bash
export WATSON_API_KEY="your_api_key"
```

---

## ▶️ Usage

### Run Speech-to-Text
```bash
python simple_speech2text.py
```

### Run LLM Processing
```bash
python simple_llm.py
```

### Run Full Application
```bash
python speech2text_app.py
```

---

## 🧠 Example Workflow

1. Provide an audio file (`downloaded_audio.mp3`)
2. Convert speech → text
3. Send text to an LLM
4. Extract key insights or summaries

---

## 📌 Example Output

**Input:**
```
"Today we discussed the product launch timeline and marketing strategy."
```

**Output:**
```
- Launch scheduled for next month
- Marketing campaign starts in 2 weeks
- Budget approval pending
```

---

## 🛠️ Tech Stack

- Python
- Speech-to-Text APIs (IBM Watson / others)
- OpenAI / Hugging Face / Watson LLM
- Requests / audio processing libraries

---

## 🔮 Future Improvements

- Real-time meeting transcription
- Speaker identification
- UI dashboard (Gradio / Flask)
- Integration with Zoom / Google Meet
- Automatic action item extraction

---

## 🤝 Contributing

Feel free to fork this repository and improve it!

---

## 📄 License

This project is for educational purposes.

---

## 🙌 Acknowledgements

- OpenAI
- IBM Watson
- Hugging Face

---

## ⚠️ Notes

- Do **NOT** upload your virtual environment (`my_env/`) to GitHub  
- Use a `.gitignore` file:

```
my_env/
__pycache__/
.env
```
