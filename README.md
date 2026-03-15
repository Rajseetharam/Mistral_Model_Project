# Mistral_Model_Project
A high-performance conversational AI chatbot built using the Mistral-7B model. Features optimized inference, context-aware responses
# Mistral-7B Chatbot (Jupyter Notebook)

This repository contains a standalone implementation of a chatbot using the **Mistral-7B-v0.1** model. It is designed to run in a GPU-accelerated environment like Google Colab.

## 🌟 Overview
The notebook demonstrates how to:
* Load the Mistral model using **4-bit quantization** (via `bitsandbytes`) to save VRAM.
* Set up a conversational pipeline using Hugging Face `transformers`.
* Implement a loop for real-time interaction with the AI.

## 🚀 How to Use
1. **Download** the `Chatbot_using_Mistral.ipynb` file.
2. **Upload** it to [Google Colab](https://colab.research.google.com/).
3. **Change Runtime:** Go to `Runtime` > `Change runtime type` > Select **T4 GPU** (or better).
4. **Run All Cells:** The notebook will handle the installation of dependencies and model downloading.

## 🛠️ Requirements
* A Hugging Face account (to access the model).
* A GPU with at least 12GB VRAM (T4 is sufficient for 4-bit).
