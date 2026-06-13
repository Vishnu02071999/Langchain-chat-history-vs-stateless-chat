# Langchain-chat-history-vs-stateless-chat
This project compares two simple chatbot implementations built with LangChain and OpenAI:

Stateless Chatbot – Processes each user message independently without storing previous interactions.
Stateful Chatbot – Stores conversation history in a list, allowing the application to maintain a record of the interaction.

The goal is to understand the importance of conversation memory and how chat history can be managed within a LangChain application.

# What You'll Learn
How to create a basic chatbot using ChatOpenAI

The difference between stateful and stateless conversations

How to store chat history in Python

How conversation context affects chatbot design

Basic usage of environment variables with python-dotenv

# Project Structure
Version 1: Chat History Tracking

Stores user messages and AI responses in a Python list.

Maintains a local record of the conversation.

Useful as a foundation for implementing memory systems.

Version 2: Stateless Chat

Sends each prompt independently.

Does not save previous messages.

Simpler implementation with lower memory requirements.

# Key Difference
Feature	            Chat History Version	      Stateless Version
Stores Messages	         ✅ Yes	                     ❌ No
Conversation Record	     ✅ Yes	                     ❌ No
Simplicity	             Moderate	                Very Simple
Memory Foundation	       ✅ Yes	                     ❌ No

Note: In the first implementation, the history is stored locally in a Python list but is not sent back to the model. Therefore, the model itself does not remember previous messages. The list simply keeps a record of the conversation.

# Technologies Used
Python
LangChain
OpenAI
python-dotenv
Purpose

This repository serves as a beginner-friendly example for understanding conversation management in LangChain applications and highlights the first step toward implementing chatbot memory and context-aware interactions.
