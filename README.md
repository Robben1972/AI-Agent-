# AI Agent with Ollama Mistral and CodeLlama

This repository contains an AI agent powered by Ollama Mistral and CodeLlama. The agent is designed to perform advanced AI tasks efficiently. Follow the instructions below to set up and start using the AI agent.

## Features

- **Ollama Mistral**: Enables robust AI functionalities.
- **CodeLlama**: Enhances the agent's capability to handle code-related tasks.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.8 or later installed on your system.
- Access to the Ollama API.
- Basic knowledge of `.env` files for storing sensitive API keys.

## Installation

1. **Clone the Repository**  
   Clone this repository to your local machine:
   ```bash
   git clone git@github.com:Robben1972/AI-Agent-.git
   cd AI-Agent-
   ```

2. **Set up a Virtual Environment (optional but recommended)**  
   Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**  
   Install the required Python packages:
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the `.env` File**  
   Create a `.env` file in the project root and add your Ollama API key:
   ```env
   LLAMA_CLOUD_API_KEY=your_ollama_api_key_here
   ```

5. **Verify the Setup**  
   Ensure the setup was successful by running the following command:
   ```bash
   python main.py
   ```

## Usage

Once installed, you can start the AI agent by running:
```bash
python main.py
```
The agent will use Ollama Mistral and CodeLlama to process your requests.

## Environment Variables

This project uses environment variables to securely store API keys. The key used by this project:

| Variable Name          | Description                   |
|------------------------|-------------------------------|
| `LLAMA_CLOUD_API_KEY` | Your Ollama API key for access |
