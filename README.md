# 🤖 Child EmoBot – Sentiment Analysis Chatbot

## 📌 Overview

**Child EmoBot** is an AI-powered chatbot designed to understand and respond to children's emotions using **Natural Language Processing (NLP)** and **sentiment analysis**.

The bot can detect emotional tone from user input and respond appropriately, making it useful for:

* Emotional support systems
* Educational tools
* Interactive chat applications

---

## 🚀 Features

* 💬 Conversational chatbot built with Rasa
* 😊 Sentiment detection (positive, negative, neutral)
* 🧠 Custom actions for dynamic responses
* 📊 NLP-based intent classification
* 🔄 Rule-based and story-based dialogue management

---

## 🛠️ Tech Stack

* **Python**
* **Rasa**
* **NLU (Natural Language Understanding)**
* **YAML configuration files**

---

## 📁 Project Structure

```
Child-EmoBot-main/
│
├── actions/               # Custom Python actions
├── data/                  # Training data (NLU, stories, rules)
├── models/                # Trained Rasa models
├── tests/                 # Test stories
├── config.yml             # Model configuration
├── domain.yml             # Bot domain (intents, entities, responses)
├── endpoints.yml          # Action server endpoints
├── credentials.yml        # Channel credentials
```

---

## ⚙️ Installation

1. Clone the repository:

```bash
git clone <your-repo-link>
cd Child-EmoBot-main
```

2. Install dependencies:

```bash
pip install rasa
```

---

## ▶️ Running the Bot

### 1. Train the model

```bash
rasa train
```

### 2. Run the action server

```bash
rasa run actions
```

### 3. Start the chatbot

```bash
rasa shell
```

---

## 🧪 Testing

Run tests using:

```bash
rasa test
```

---

## 🧠 How It Works

1. User inputs a message
2. Rasa NLU processes the text
3. Intent and sentiment are identified
4. Dialogue manager selects the response
5. Custom actions generate dynamic replies

---

## 🎯 Use Cases

* Child emotional support chatbot
* Educational assistant
* Mental health awareness tools
* Interactive AI learning systems

---

## 📌 Future Improvements

* 🔍 Advanced sentiment analysis using ML models
* 🗣️ Voice input/output integration
* 🌐 Web or mobile deployment
* 📈 Analytics dashboard

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repo and submit a pull request.

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Author

Developed as a project to explore NLP, sentiment analysis, and conversational AI using Rasa.
