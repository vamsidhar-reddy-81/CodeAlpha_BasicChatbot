# Basic Chatbot

A simple rule-based chatbot written in Python that runs in the terminal. It replies to a few fixed messages and exits when you type `bye`.

---

## Features

- Runs in the command line
- Case-insensitive input (`Hello`, `HELLO` and `hello` all work)
- Understands these messages:

| You type | Bot replies |
|---|---|
| `hello` | Hi! |
| `how are you` | I'm fine, thanks! |
| `bye` | Goodbye! (and the program ends) |
| anything else | Sorry, I don't understand that. |

## Tech and concepts

Python 3 | functions | `while` loop | `if / elif / else` | string methods (`lower()`)

## Project structure

```
CodeAlpha_BasicChatbot/
├── BasicChatBot.py   # Chatbot program
└── README.md
```

## How to run

1. Install [Python 3](https://www.python.org/downloads/)
2. Clone the repository and run:
   ```bash
   git clone https://github.com/vamsidhar-reddy-81/CodeAlpha_BasicChatbot.git
   cd CodeAlpha_BasicChatbot
   python BasicChatBot.py
   ```

## Sample run

```
Simple Chatbot
Type 'bye' to exit.

You: hello
Bot: Hi!
You: how are you
Bot: I'm fine, thanks!
You: what is ai
Bot: Sorry, I don't understand that.
You: bye
Bot: Goodbye!
```

## Ideas to improve

- Add more questions and answers using a dictionary
- Make the matching smarter (keywords instead of exact sentences)
- Connect the chatbot to an NLP library or an AI API

## Author

**Vamsidhar Reddy**
GitHub: [vamsidhar-reddy-81](https://github.com/vamsidhar-reddy-81) | LinkedIn: [Vamsidhar Reddy](https://www.linkedin.com/in/morreddy-gari-vamsidharreddy-4b0640378/)
