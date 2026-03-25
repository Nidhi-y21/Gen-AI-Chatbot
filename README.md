

# 🤖 GenAI Chatbot using Gemma 2 (2B)

A lightweight Generative AI chatbot built using **Google's Gemma-2-2B-IT model** in Python. This chatbot can generate human-like responses and is designed for easy customization and experimentation.

---

## 🚀 Features

* 💬 Conversational AI chatbot
* ⚡ Powered by **Gemma-2-2B-IT**
* 🧠 Context-aware responses
* 🛠️ Easy to modify and extend
* 🖥️ Runs locally (CPU/GPU supported)

---

## 🧰 Tech Stack

* Python 🐍
* Hugging Face Transformers 🤗
* PyTorch 🔥
* Gemma Model (google/gemma-2-2b-it)

---

## 📂 Project Structure

```
├── app.py              # Main chatbot script
├── requirements.txt    # Dependencies
├── README.md           # Project documentation
└── utils/              # Helper functions (optional)
```

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/genai-chatbot-gemma.git
cd genai-chatbot-gemma
```

### 2. Create virtual environment (recommended)

```bash
python -m venv venv
venv\Scripts\activate   # On Windows
source venv/bin/activate  # On Mac/Linux
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Setup

1. Install Hugging Face CLI:

```bash
pip install huggingface_hub
```

2. Login to Hugging Face:

```bash
huggingface-cli login
```

3. Accept access for the model:
   👉 [https://huggingface.co/google/gemma-2-2b-it](https://huggingface.co/google/gemma-2-2b-it)

---

## ▶️ Usage

Run the chatbot:

```bash
python app.py
```

Example interaction:

```
You: Hello!
Bot: Hi there! How can I help you today?
```

---

## ⚡ Model Details

* Model: `google/gemma-2-2b-it`
* Type: Instruction-tuned LLM
* Parameters: 2 Billion
* Developer: Google



## 🧠 How It Works

1. Loads the Gemma model using Hugging Face Transformers
2. Takes user input from terminal
3. Generates response using text generation pipeline
4. Displays output in conversational format



## 📌 Requirements

* Python 3.8+
* Minimum 8GB RAM (16GB recommended)
* GPU (optional, but improves performance)



## 🔧 Customization

You can modify:

* Temperature (creativity)
* Max tokens
* Prompt design
* UI (convert to Streamlit / Flask app)



## 🌟 Future Improvements

* 🌐 Web interface (Streamlit/Flask)
* 🧾 Chat history memory
* 🔊 Voice input/output
* 📊 Logging and analytics



## 🤝 Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request.



## 📜 License

This project is licensed under the MIT License.



## 🙌 Acknowledgements

* Google AI for Gemma Model
* Hugging Face for Transformers library



## 💡 Author

**Nidhi Yadav**
Aspiring Data Scientist 🚀


