
# Chat with GPT-4 Using OpenAI API :fire:

This project is a simple interface for interacting with OpenAI's GPT-4 model directly through the terminal. The program takes user input, sends it to the GPT-4 model, and displays the responses in real-time using streaming.

## Features :sparkles:

- **Continuous interaction with the model**: Chat with GPT-4 in real-time.
- **Streaming support**: Responses are displayed as they are generated.
- **Simplified API setup**: Uses an API key for authentication, with support for multiple retries in case of network failures.
- **"Exit" command**: Close the program at any time by typing "exit."

## Prerequisites :tools:

- Python 3.8 or higher
- `openai` library
- OpenAI API key (set in the `key_openai` variable or as an environment variable)

## How to Use :rocket:

1. Clone this repository:
   ```bash
   git clone https://github.com/your_username/chat-gpt-terminal.git
   cd chat-gpt-terminal

## Install the dependencies:
pip install openai

## Set your OpenAI API key:
Option 1: Edit the key_openai variable in the script and add your API key.
Option 2: Set it as an environment variable:
export OPENAI_API_KEY="your_api_key_here"

## Run the script:
python chat_with_gpt.py
Start chatting! Type your messages, and GPT-4 will respond. To exit, type exit.

## Example Usage 📜
You: What is Python?
GPT-4: Python is a high-level programming language widely used for its simplicity and power. It supports multiple paradigms, including object-oriented, functional, and procedural programming...
Customization 🎨
Model: Change the model by replacing "gpt-4o" with another available model in the model parameter.
Retry Limit: Adjust the maximum number of retries (default: 10) in the max_retries parameter.
Contributing 🤝
Contributions are welcome! Feel free to open issues or submit pull requests with suggestions and improvements.
