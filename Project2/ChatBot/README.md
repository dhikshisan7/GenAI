# 🤖 D-Bot – AI Chatbot

D-Bot is an AI-powered chatbot built using **Python, Hugging Face Transformers, Qwen2.5-0.5B-Instruct, and Gradio**. It allows users to interact with an AI assistant, ask questions, explore topics, and maintain conversation context during a chat session.

## ✨ Features

- 💬 Interactive AI chatbot interface
- 🧠 Uses the Qwen2.5-0.5B-Instruct language model
- 🗂️ Maintains conversation history during a chat
- ➕ Start a new conversation
- 🗑️ Clear the current conversation
- 🔄 Switch between saved conversations during the running session
- 💡 Suggested prompts for Generative AI, Python, and fun facts
- 🎨 Custom blue-and-white Gradio interface

## 🛠️ Technologies Used

- Python
- Hugging Face Transformers
- Qwen2.5-0.5B-Instruct
- PyTorch
- Gradio
- Google Colab

## 🚀 How to Run

### 1. Open the Notebook

Open `ChatBot_Dhikshi.ipynb` in Google Colab.

### 2. Install the Required Libraries

Run the installation cell:

```python
!pip install transformers gradio -q
```

### 3. Load the AI Model

The notebook loads the following model from Hugging Face:

```python
MODEL = "Qwen/Qwen2.5-0.5B-Instruct"
```

### 4. Run the Notebook

Execute the notebook cells in order. The model will load, and the Gradio interface will be created.

### 5. Chat with D-Bot

Run the final cell to launch the chatbot. The notebook uses Gradio's sharing option to provide access through a temporary public link.

## 🧪 Example Questions

- What is Artificial Intelligence?
- Explain Generative AI with an example.
- Help me understand Python.
- How does AI help manage traffic?
- Tell me an interesting fun fact.

## 📌 Project Status

**Status:** Developed and tested in Google Colab using Gradio.

**Deployment:** Not permanently deployed. The Gradio share link is intended for temporary access while the notebook session is running.

## 🎯 Project Objective

The objective of this project is to build a simple conversational AI application that demonstrates the use of a pretrained language model, conversation history, and a user-friendly chatbot interface.

## 👩‍💻 Author

**Dhikshi Ramesh**

---

*Note: Chat history is maintained in the running notebook session. It is not configured as permanent database storage. AI-generated responses may occasionally be inaccurate.*
