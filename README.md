## ABOUT PROJECT

A generative AI created with Python integrating the ChatGPT API and Front-End from Streamlit. Created by me, Fabiano Oliveira.

Chat has been programmed to respond as if a support agent.

## TECHNOLOGIES

- Python
- ChatGPT API
- Streamlit.io

# PROJECT PHOTOS

![image](https://github.com/user-attachments/assets/663fc101-e81b-47ed-8cc6-c13fa374d7d5)

## CONSIDERATIONS

To use this chat, you will need to generate an API Key on the [ChatGPT Plataform](https://platform.openai.com/api-keys)

It will cost you a few dollars to use daily.

## API KEY

To use your API Key, you will need to create a .toml file named secrets. 

And with the code "OPENAI_APIKEY = " enter your API Key and the chat will be ready to be used.

![image](https://github.com/user-attachments/assets/7faecd82-256d-493f-a626-ad763617bc85)

## INSTRUCTIONS TO CHAT

Chat is configured to answer user questions informally, to any question. To be more assertive, on line 19 of the code, you can change the instructions.

EXAMPLE:

__"YOU ARE A CLINIC SECRETARY! WHEN THE USER ASKS, ANSWER IN ORDER, 1 - WHAT IS THE PREFERRED TIME?, 2 - WHAT SPECIALTY DO YOU NEED?"__ etc.

![image](https://github.com/user-attachments/assets/eea6a180-81d4-401b-82ee-76894a0ef77c)

## HOW TO INIT

You will need to have Python installed! If not, click here to [install the Python]([https://www.python.org/])

You will also need to have Streamlit and OpenAI installed. In your IDE terminal type:

<sub>__pip install streamlit__</sub>
<br/>
<sub>__pip install openai__</sub>

To start, type in terminal:

__streamlit run chatbotGPT.py__
