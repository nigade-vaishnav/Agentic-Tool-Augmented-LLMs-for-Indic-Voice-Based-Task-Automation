# 🚀 Agentic Tool-Augmented LLMs for Indic Voice-Based Task Automation

> A multilingual **Agentic AI assistant** that converts **voice → intent → tool execution** for real-world task automation in **English, Hindi, and Marathi**.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Whisper](https://img.shields.io/badge/OpenAI-Whisper-green)
![Colab](https://img.shields.io/badge/Google-Colab-orange)
![LLM](https://img.shields.io/badge/AI-Agentic-purple)

---

## ✨ Project Overview

Traditional LLMs are great at generating text, but they often **cannot autonomously act on user requests**.

This project bridges that gap by building an **Agentic AI system** capable of:

* 🎤 Multilingual **voice input understanding**
* 🧠 **Intent detection** from natural language
* 🛠️ Dynamic **tool selection and execution**
* 🌍 Support for **English + Hindi + Marathi**
* ⚡ Real-time execution inside **Google Colab**

The system currently supports:

* ⏰ Current time (IST)
* ➕ Natural language calculations
* 🙏 Greetings
* 🤖 Name / identity queries
* 📅 Date queries
* 😂 Basic joke generation

---

## 🏗️ Architecture

```text
Voice Input → Whisper ASR → Intent Router → Tool Calling → Response
```

### Core Pipeline

1. **Speech-to-Text** → OpenAI Whisper Base
2. **Intent Detection** → custom multilingual agent router
3. **Tool Invocation** → calculator / time / response tools
4. **Structured Output** → intent + action + result

---

## 🎯 Key Features

### 🎤 Multilingual Voice AI

Supports:

* English
* Hindi
* Marathi

### 🧠 Agentic Tool Routing

The assistant autonomously maps user intent to tools:

* `get_time()`
* `calculator()`
* `greeting()`
* `ask_name()`
* `get_date()`

### 🧮 Natural Language Math

Understands:

* `5 plus 7`
* `10 minus 2`
* `6 into 4`
* Hindi / Marathi phrasing support

### 🇮🇳 India-first Localization

* IST timezone correction
* Indic speech workflows
* Hindi + Marathi command normalization

---

## 📸 Demo Scenarios

### Text Demo

```python
run_agent("What is the time now?")
run_agent("5 plus 7")
```

### Voice Demo

```python
result = model.transcribe(audio_file, language="hi")
run_agent(result["text"])
```

---

## 🧪 Sample Output

```python
{
  "input": "5 plus 7",
  "intent": "calculator",
  "output": "12"
}
```

```python
{
  "input": "Abhi time kya hai",
  "intent": "get_time",
  "output": "2026-03-30 08:50:58 AM IST"
}
```

---

## 🛠️ Tech Stack

* **Python**
* **OpenAI Whisper (base)**
* **Google Colab**
* **Regex-based NLP normalization**
* **Agentic Tool Routing**
* **Optional GPT API upgrade path**

---

## 🚀 Recruiter Highlights

This project demonstrates strong skills in:

* Applied **LLM systems design**
* **Agentic AI / tool calling** workflows
* **Speech AI (ASR)**
* **Multilingual NLP**
* Rapid prototyping in **Colab / Python**
* Real-world **AI product thinking**

### 💼 Relevant Roles

* AI Engineer
* ML Engineer
* Applied Scientist
* NLP Engineer
* LLM / GenAI Engineer
* AI Product Prototyping

---

## 🔮 Future Scope

* 🌐 GPT-powered semantic tool routing
* 🗺️ Maps + weather + search APIs
* 📅 Calendar / reminder automation
* 🧠 Multi-agent orchestration
* 📱 Mobile deployment with Flutter frontend
* 🎙️ Better Indic ASR fine-tuning

---

## 👨‍💻 Author

**Vaishnav Nigade**

* B.Tech CSE (AI & DS)
* IIIT Kottayam
* Focus: **Agentic AI, LLM Systems, MLOps, AI Products**

---

## ⭐ Why this project stands out

Instead of building another chatbot, this project focuses on the next generation of AI:

> **AI that can listen, understand, decide, and act.**

That is the foundation of real-world **Agentic AI systems**.
