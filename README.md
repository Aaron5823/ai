# ai
Personal projects 
# Simple AI Chatbot

This is a simple AI chatbot implemented in Python. The chatbot uses hardcoded responses stored in a JSON file to interact with users.

## Features

- Responds to common greetings like "hello", "hi", etc.
- Engages in simple conversations like "how are you?".
- Provides responses to expressions of gratitude such as "thank you".
- Tells jokes upon request.

## Requirements

- Python 3.x

## Usage

1. Clone the repository or download the files.
2. Make sure you have Python installed on your system.
3. Run the `chatbot.py` script using the command: `python chatbot.py`.
4. Interact with the chatbot by typing your messages in the terminal.

## Adding Custom Responses

You can customize the chatbot's responses by editing the `training_data.json` file. Each user input is associated with a list of possible responses. Simply add or modify the responses as needed.

## Example JSON Structure

```json
{
  "hello": ["Hello!", "Hi there!", "Hey!"],
  "how are you?": ["I'm good, thank you.", "Feeling great!", "Pretty good."],
  "bye": ["Goodbye!", "See you later!", "Bye! Have a nice day!"],
  "thank you": ["You're welcome!", "No problem!", "Glad to help!"],
  "tell me a joke": ["Why don't scientists trust atoms? Because they make up everything!", "I told my wife she was drawing her eyebrows too high. She looked surprised."]
}

