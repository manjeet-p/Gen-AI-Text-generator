# Gen-AI-Text-generator
Text Generator using GPT-2 (Google Colab / Gradio)
Overview

This project implements a Text Generation system using the GPT-2 language model from Hugging Face Transformers. It allows users to input a prompt and generate coherent text using a simple Gradio web interface. The notebook is fully compatible with Google Colab and runs on CPU or GPU.

Features

Uses GPT-2 pre-trained language model

Supports custom prompts

Adjustable parameters:

Max new tokens

Temperature (creativity control)

Interactive Gradio UI

Automatic device selection (CPU / CUDA)

Technologies Used

Python

Hugging Face transformers

PyTorch

Gradio

Installation

Run the following commands in Google Colab or Jupyter Notebook:

pip install transformers gradio accelerate

Model Initialization

Model: gpt2

Tokenizer: GPT2Tokenizer

Framework: PyTorch

Device: CUDA if available, otherwise CPU

How It Works

Load GPT-2 tokenizer and model

Accept user input (prompt)

Generate text using:

max_new_tokens

temperature

Decode tokens into readable text

Display output via Gradio web app

Gradio Interface

The interface includes:

Textbox for prompt input

Slider for:

Maximum new tokens

Temperature

Output textbox for generated text

The application launches locally using:

demo.launch()

Example Prompt
You are a school teacher. Write a short story for children.

Output

The model generates a short, coherent story based on the given prompt and selected parameters.

Use Cases

Educational demonstrations

AI/ML mini projects

NLP learning experiments

College assignments

Prompt engineering practice

Notes

GPT-2 is a lightweight model; outputs are fast but may lack deep reasoning

Increasing temperature increases creativity but may reduce coherence

Suitable for beginners in NLP and Transformers
