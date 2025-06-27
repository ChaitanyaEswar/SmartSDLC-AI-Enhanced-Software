# SmartSDLC – AI-Enhanced Software

# 💡 SmartSDLC Pro – AI-Powered SDLC Automation Suite

![SmartSDLC Pro Banner](https://img.shields.io/badge/AI%20Model-IBM%20Granite-blue?style=for-the-badge)
![Language Support](https://img.shields.io/badge/Languages-Python%2C%20Java%2C%20C%2C%20C%2B%2B%2C%20JS%2C%20More-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-lightgrey?style=for-the-badge)

> **SmartSDLC Pro** is a fully integrated AI application that automates the **Software Development Life Cycle (SDLC)** tasks using IBM Granite's LLMs. It supports multiple programming languages and provides end-to-end assistance in code generation, debugging, test creation, documentation, and even architecture consulting—all within an elegant Gradio-based interface.

---

## 🚀 Features

- ✅ **PDF Requirements Analysis**
  - Extracts and analyzes software requirements from PDF documents
  - Provides summaries, complexity analysis, and priority mappings

- 💻 **Code Generation**
  - Generate clean, production-ready code from user stories
  - Supports error handling, comments, and modern best practices

- 🐞 **Debugging**
  - Automatically finds bugs and provides corrected code with detailed explanations

- 🧪 **Test Case Generation**
  - Creates unit tests based on standard frameworks (e.g., `pytest`, `JUnit`, `GoogleTest`)

- 📝 **Code Documentation**
  - Generates documentation with purpose, I/O, examples, and architectural notes

- 💬 **AI Consultant**
  - Ask architecture, design, or best practice questions and get professional advice

- ⭐ **Feedback System**
  - Users can submit ratings and feedback, which are logged for review

---

## 🛠️ Technologies Used

| Component        | Technology                            |
|------------------|----------------------------------------|
| Frontend         | Gradio UI (with Tabs, Dropdowns, etc.) |
| Backend          | Python 3, Transformers, PyTorch        |
| AI Model         | IBM Granite 3.3 (2B Instruct)          |
| PDF Parsing      | PyPDF2                                 |
| File Handling    | tempfile, JSON, datetime               |

---
## requirements.txt includes:
gradio
transformers
torch
PyPDF2
## 🧠 Model Info
Model ID: ibm-granite/granite-3.3-2b-instruct

Provider: IBM (via Hugging Face Transformers)

Inference: Token generation with torch.float16 and cuda if available
## 🧪 Supported Languages & Testing Frameworks:
| Language   | Test Framework |
| ---------- | -------------- |
| Python     | pytest         |
| Java       | JUnit          |
| JavaScript | Jest           |
| C++        | Google Test    |
| C          | Unity          |
| C#         | NUnit          |
| TypeScript | Jest           |
| Swift      | XCTest         |
| Kotlin     | JUnit          |
| Go         | (Add support)  |

## ✨ Acknowledgements
IBM Granite for the powerful LLMs

Gradio for the UI framework

Hugging Face Transformers for model integration
