# 🚀 Fine-Tuning Gemma 2B with LoRA on Google Colab

This project demonstrates how to fine-tune the open-source **Gemma3 1B** model using **LoRA (Low-Rank Adaptation)** in **Google Colab**, with a dataset downloaded from **Kaggle**.

> No Google Cloud or Vertex AI needed — this is a simple and reproducible approach for beginners using just Colab and a local Kaggle dataset!

---

## 📚 Project Overview

In this hands-on tutorial, we:
- Use **Kaggle API** to download the **Gemma 3** dataset (a `.json` text dataset)
- Set up Kaggle authentication in Google Colab
- Apply basic preprocessing and tokenization
- Fine-tune **Gemma 1B** using **LoRA** for memory-efficient training
- Evaluate the model with example prompts

---

## 🛠️ Tech Stack

- ✅ Google Colab
- ✅ Hugging Face Transformers
- ✅ PEFT (for LoRA)
- ✅ Kaggle API
- ✅ JSON text dataset

---

## 📁 Dataset

We use the **Gemma 3** dataset from Kaggle:

1. I created a Kaggle account and searched for "Gemma 3"
2. I navigated to **Settings > API > Create New API Token**
3. This downloaded a `kaggle.json` file containing my Kaggle **username** and **API key**
4. I uploaded this file to **Google Colab** and set it as a secret environment variable for secure access

---

## 🧪 How to Run

1. Open the [Colab Notebook](link-to-your-colab)  
2. Upload your `kaggle.json` file  
3. Follow the notebook step-by-step:
   - Install libraries
   - Authenticate Kaggle
   - Download and load the dataset
   - Fine-tune Gemma with LoRA
   - Test the model

---

## 💡 What You’ll Learn

- How to securely use Kaggle datasets in Colab
- Basics of LoRA fine-tuning with Hugging Face + PEFT
- Preprocessing and tokenizing text data
- Running and testing a fine-tuned LLM on your custom data

---

## 📦 Output

- A fine-tuned Gemma model on your dataset
- Code that can be reused for similar LoRA fine-tuning tasks
- A reproducible, cloud-free pipeline for quick experimentation

---

## 🙋‍♀️ Author

👩‍💻 [Geeta Kakrani](https://kanishkait.in/) — Google Developer Expert (AI/ML), Corporate Trainer, and Speaker on Generative AI

---

## 📝 License

This project is open-source under the [MIT License](LICENSE).

---

