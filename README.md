# MultiLanguage-Code-Assistant-using-CodeLama-
This project provides a simple chatbot interface built with **Gradio** that communicates with a locally hosted **CodeGeni model API** (`http://localhost:11434/api/generate`). It allows users to send prompts and receive generated responses, maintaining conversation history.

## Features
- **Chat History:** Maintains the conversation context by appending previous prompts.
- **API Integration:** Sends requests to a local CodeGeni model via REST API.
- **Gradio Frontend:** Offers a user-friendly interface for interaction.

## Requirements
- Python 3.8+
- `requests`
- `gradio`
