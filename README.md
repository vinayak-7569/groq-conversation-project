# groq-conversation-project
Project Overview
This repository contains a Google Colab notebook that demonstrates two main functionalities:

Conversation Manager:

Manages chat history with constraints on the number of turns and character count.
Automatically summarizes the conversation after a set number of exchanges using GROQ’s Llama-3 API.
User Details Extraction:

Extracts structured user information (name, email, phone, location, age) from chat messages using function calling with the GROQ API.
Includes masking of sensitive information for privacy.
Features
Chat History Management:
Truncates by turn and character limit, and summarizes after every k-th message.
Function Calling:
Uses a JSON schema to extract user details directly from chat.
Sensitive Data Masking:
Masks emails, phone numbers, names, and locations for privacy.
Easy to Customize:
Parameters like max turns, character limit, and summarization frequency are adjustable.
How to Run the Notebook
Open Google Colab

Download the notebook from this repository and upload it to Google Colab.
Install Dependencies

The notebook installs the required OpenAI package automatically:
python
Copy code
!pip uninstall -y openai
!pip install --quiet openai==0.28.0
Set Up API Key

When prompted, enter your GROQ API key securely using the input box.
Run All Cells

Execute each cell in order for full demonstration.
Sample chats and outputs are provided for testing.
Requirements
Python 3
openai==0.28.0
GROQ API Key
Sign up at groq.com to obtain your API key.
Sample Usage
Conversation Manager
See how chat history is managed, summarized, and displayed.
User Details Extraction
Extracts and validates user details from sample chat messages.
Data Masking
Demonstrates masking of sensitive information in chat logs.
Repository Contents
your_notebook.ipynb — Main notebook with all code, comments, and output samples.
README.md — This documentation.
Contact & Contribution
If you have suggestions, please open an issue or submit a pull request!

