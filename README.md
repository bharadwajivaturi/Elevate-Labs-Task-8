# Elevate-Labs-Task-8
Build a Chatbot using if-else
# Simple Rule-Based Chatbot

## Overview
This is a basic rule-based chatbot implemented in Python. The chatbot responds to user inputs based on predefined patterns and keywords. It can handle greetings, farewells, simple questions about weather/time, and some basic facts.

## Features
- Responds to various greetings (hi, hello, hey)
- Handles farewells (bye, goodbye)
- Can answer simple questions about:
  - Weather
  - Time
  - Basic facts (capital of India, largest planet)
- Tells a simple joke
- Responds to emotional states (happy, sad, angry)
- Provides help/instructions when asked

## How to Use
- Run the `chatbot.py` script in a Python environment
- Type your messages to interact with the bot
- Type 'exit' or 'quit' to end the conversation

## Implementation Details
- Uses simple string matching with `if-elif-else` logic
- Converts all input to lowercase for case-insensitive matching
- Basic error handling for unrecognized inputs
- No external dependencies required

## Limitations
- Limited knowledge base
- No memory or context between messages
- No actual weather/time data (just prompts)
