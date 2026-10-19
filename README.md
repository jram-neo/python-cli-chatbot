# CLI Chatbot

A command-line chatbot in Python that sends a single prompt to an AI model through the OpenRouter API and prints the reply.

## Setup

```bash
git clone https://github.com/jram-neo/cli-chatbot.git
cd cli-chatbot
pip install -r requirements.txt
```

Create a `.env` file in the project folder:
```
OPENROUTER_API_KEY=your_key_here
```

Get a key at https://openrouter.ai

## Usage

```bash
python main.py "What is a Python decorator?"
```

Add `--verbose` to also see the prompt and token counts:
```bash
python main.py "What is a Python decorator?" --verbose
```
