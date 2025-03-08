# AI Chatbot using FastAPI & Gradio

This project provides an AI-powered chatbot built using **FastAPI** for API interactions and **Gradio** for the user interface. The chatbot is powered by **DeepScaler** via **Ollama**.

## Features
- RESTful API for chatbot interactions
- Web-based chatbot UI using Gradio
- Powered by DeepScaler and Ollama for intelligent responses
- Lightweight and easy to deploy

## Installation

1. Clone the repository:

   git clone [https://github.com/your-username/ollama-chatbot.git](https://github.com/srus1608/AI-Chatbot-using-FastAPI-Gradio/tree/main)
   cd ollama-chatbot
2.Install dependencies:

  pip install fastapi uvicorn gradio ollama

3.Running the API
  Start the FastAPI server:

    uvicorn chatbot_api:app --host 0.0.0.0 --port 8000
This will start the chatbot API at http://localhost:8000.

4.Running the Chatbot UI
Launch the Gradio chatbot interface:

python chatbot_ui.py
This will start a web-based chatbot UI where you can interact with the AI.

## API Endpoints
GET / → Returns a welcome message
GET /chat?message=your_message → Sends a message to the chatbot and receives a response
Example:
curl "http://localhost:8000/chat?message=Hello"

## Dependencies
FastAPI: For API development.
Gradio: For the chatbot's UI.
Ollama: For AI-driven chatbot responses.
