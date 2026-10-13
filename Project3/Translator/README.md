# 🌐 English to Tamil AI Translator

An AI-powered language translation project that translates English text into Tamil using a pretrained multilingual sequence-to-sequence model from Hugging Face. The project provides a simple and interactive web interface built with Gradio.

## ✨ Features

- 🔤 Translate English text into Tamil
- 🤖 Uses a pretrained AI translation model
- 🌐 Supports text-based translation
- 🖥️ Simple and interactive Gradio interface
- ⚡ Supports GPU acceleration when available
- 📝 Handles input text and displays the Tamil translation

## 🛠️ Technologies Used

- Python
- PyTorch
- Hugging Face Transformers
- NLLB-200
- SentencePiece
- Gradio
- Google Colab

## 🧠 Model Used

**Model:** `facebook/nllb-200-distilled-600M`

The notebook uses the NLLB-200 distilled multilingual model for English-to-Tamil translation.

## 🚀 How to Run

### 1. Open the Notebook

Open `English_to_Tamil_Translator_Dhikshi.ipynb` in Google Colab.

### 2. Install the Required Libraries

Run the following command in a notebook cell:

```python
!pip install -q transformers sentencepiece gradio
```

### 3. Load the Model

The notebook loads the pretrained model and tokenizer from Hugging Face:

```python
MODEL_NAME = "facebook/nllb-200-distilled-600M"
```

### 4. Run the Notebook

Execute the cells in order to load the model, initialize the translation function, and create the Gradio interface.

### 5. Translate English Text

Enter any English sentence in the input box and view the generated Tamil translation.

## 💡 Example

**Input (English):**

```text
I am learning artificial intelligence.
```

**Output (Tamil):**

The model generates the corresponding Tamil translation.

## ⚙️ How It Works

1. The user enters English text.
2. The tokenizer converts the input text into model-readable tokens.
3. The pretrained NLLB-200 model generates the Tamil translation.
4. The generated tokens are decoded into Tamil text.
5. Gradio displays the translated text to the user.

## 📌 Project Status

**Status:** Implemented in a Jupyter notebook using Google Colab and Gradio.

**Deployment:** Not permanently deployed. The notebook uses `share=True` to create a temporary Gradio sharing link while the session is running.

## 🎯 Project Objective

The objective of this project is to demonstrate how pretrained multilingual AI models can be used to build a simple language translation application, making English text accessible to Tamil readers.

## 👩‍💻 Author

**Dhikshitha R**

---

*Note: Translation quality may vary depending on the input text. The project is designed for English-to-Tamil translation and may not always produce perfectly accurate results.*
