# AI-Agent-for-chatbot-with-Conversational-ReAct

This chatbot application integrates Hugging Face's Transformers for natural language understanding and generation, Pinecone for vector database capabilities, and LangChain for conversational memory and agent logic. It is designed to provide a conversational interface where users can ask questions or have a dialogue, with the chatbot leveraging a knowledge base stored in Pinecone for responses.

## Features

- Conversational AI using Hugging Face's Transformer models.
- Vector database integration with Pinecone for storing and retrieving knowledge base documents.
- Conversational memory for context-aware interactions.
- Document embedding and retrieval for answering queries with relevant information.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.7+
- A Pinecone API key and a Pinecone vector database set up.
- An environment for running Python scripts (e.g., terminal, command prompt, IDE).

## Installation

1. **Clone the repository:**


2. **Install dependencies:**

Install the required Python packages using the provided `requirements.txt`:


3. **Configuration:**

- Ensure you have a Pinecone account and an API key. Update the `PINECONE_API_KEY` in the `app.py` script with your actual Pinecone API key.
- Adjust any model or tokenizer names in `app.py` as needed, based on your project's requirements.

## Usage

To run the chatbot application, execute the following command in your terminal:


Interact with the chatbot by typing your questions or messages into the console. Type `quit` to exit the chat loop.

## Customization

- You can customize the chatbot by changing the Hugging Face model used for conversations or document embeddings.
- Modify the `app.py` script to include additional functionalities or integrate with other services or databases.
