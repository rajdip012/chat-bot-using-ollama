# Enhanced Q&A Chatbot With Ollama

This project is an enhanced Q&A chatbot built using Ollama and Streamlit. The chatbot uses the LangChain library for managing language models and prompts, and it allows users to ask questions and get responses based on the selected model.

## Features

- Interactive chatbot interface using Streamlit.
- Supports multiple Ollama models.
- Adjustable parameters for fine-tuning responses.
- Secure handling of API keys and environment variables.

## Installation

1. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

3. Create a `.env` file in the root directory and add your LangChain API key:
    ```env
    LANGCHAIN_API_KEY=your_api_key_here
    ```

## Usage

1. Run the Streamlit application:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Select the Ollama model, adjust the parameters (temperature and max tokens), and ask your questions.

## Project Structure

- `app.py`: The main application file containing the Streamlit app and the chatbot logic.
- `requirements.txt`: List of required packages for the project.
- `.env`: Environment file to securely store API keys and other sensitive information.

## Environment Variables

Ensure the following environment variables are set in your `.env` file:
- `LANGCHAIN_API_KEY`: Your LangChain API key.
