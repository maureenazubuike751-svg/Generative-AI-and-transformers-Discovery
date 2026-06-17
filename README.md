# Generative-AI-and-transformers-Discovery
Mini project 
# Generative AI & Transformers - Text Analysis and Generation

## 📌 Project Overview
This project demonstrates the core capabilities of Transformer-based Generative AI models. It implements three key natural language processing (NLP) tasks using the Hugging Face `transformers` library:

- **Sentiment Analysis** – Classifies text as positive or negative.
- **Text Generation** – Generates coherent text continuations from a prompt.
- **Summarization** – Condenses long articles into concise summaries.

## 🚀 Features
- Real-time sentiment scoring with confidence levels.
- GPT-2 based text generation with adjustable temperature settings.
- BART-based article summarization.
- Analysis of AI limitations, including **hallucinations** and **bias** detection.

## 🛠️ Technologies Used
- **Python 3.12**
- **Hugging Face Transformers**
- **PyTorch**
- **Google Colab**

## 📂 Project Structure
The entire code is contained in a single Jupyter Notebook (`Generative_AI_Transformers.ipynb`) and covers:
1.  **Discovery Phase** – Initializing NLP pipelines.
2.  **Technical Phase** – Running sentiment, generation, and summarization tests.
3.  **Action Phase** – Business workflow integration and hallucination analysis.

## 📊 Sample Outputs
- **Sentiment:** "I absolutely love this product!" → POSITIVE (99% confidence).
- **Generation:** Prompt: "The future of artificial intelligence..." → Generates a 50-token continuation.
- **Summarization:** Condenses a 150-word healthcare AI article into 2 concise sentences.

## ⚠️ Key Observations
- **Hallucination:** The text generation model sometimes produces plausible but unverified facts.
- **Bias:** The sentiment model fails to detect sarcasm (e.g., "Oh great, another meeting" is classified as positive).

## 🔧 How to Run
1.  Open the notebook in Google Colab.
2.  Run the first cell to install dependencies (`transformers`, `torch`).
3.  Run the subsequent cells to execute the pipelines and view outputs.

## 👤 Author
[Your Name Here]

## 📅 Submission Date
[Insert Date]
