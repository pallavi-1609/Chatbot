# Chatbot
An interactive chatbot UI using Qwen LLM with Gradio. It loads Hugging Face's Qwen model for text generation and displays user-bot conversations in a clean chat interface. Easily deployable on local or Hugging Face Spaces. Supports GPU acceleration for faster inference.
#  Hugging Face LLM Chatbot using Gradio
An interactive chatbot application that leverages Hugging Face's **Qwen3-4B model** for text generation. The chatbot is built using **Transformers, Gradio, and Accelerate**, providing a simple web interface for real-time conversations.

## Features
- Uses **Qwen/Qwen3-4B** model from Hugging Face.
- Simple **Gradio UI** with chat bubbles.
- Supports text generation with citation-based responses.
- Deployable via **Colab or local Jupyter**.

## Setup Instructions
-----------------------------------
 1. ####Clone the Repository
git clone https://github.com/pallavi-1609/Chatbot.git
cd Chatbot
--------------------------------------------------------
####2. Install Required Libraries
      pip install -r requirements.txt
---------------------------------------------------
#### 3. Hugging Face Token
Create a .env file in the project root:
#### HUGGINGFACE_TOKEN=your_hf_token_here
Ensure .env is listed in .gitignore to keep it private.
-----------------------------------------------------
4. Run the Notebook
Open Chatbot.ipynb in Google Colab or Jupyter Notebook.

Execute all cells.
--------------------------------------------------------
 Important Notes
Do NOT expose your Hugging Face Token in public repositories.
For Colab users, manually set the token in the notebook using:
import os
os.environ['HUGGINGFACE_TOKEN'] = "your_hf_token_here"
----------------------------------------------------------
##  Demo
* Gradio link -https://8265d2d86550704120.gradio.live/
* <img width="940" height="733" alt="image" src="https://github.com/user-attachments/assets/8669afea-3ad7-479e-8c4d-f4d499d4effd" />


--------------------------------------------------------------
##  License
This project is licensed under the MIT License.



