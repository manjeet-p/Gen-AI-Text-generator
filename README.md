# Text Generator using GPT-2

## Overview
This project implements a **Text Generation system** using the **GPT-2 language model** from Hugging Face. It provides an interactive **Gradio-based web interface** where users can enter a text prompt and generate coherent text. The notebook is fully compatible with **Google Colab**.

---

## Features
- Pre-trained **GPT-2** language model
- Custom text prompt input
- Adjustable generation parameters:
  - Maximum new tokens
  - Temperature (controls creativity)
- Interactive **Gradio UI**
- Automatic CPU / GPU detection

---

## Technologies Used
- Python
- PyTorch
- Hugging Face Transformers
- Gradio

---

## Installation
Run the following command in Google Colab or Jupyter Notebook:

```bash
pip install transformers gradio accelerate
