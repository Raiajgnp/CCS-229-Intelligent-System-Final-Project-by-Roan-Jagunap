# 🤖 Create Content with Generative AI
### by: Roan H. Jagunap | BSCS 3B - AI | CCS 229 Intelligent Systems Final Project ###

## 𐙚 Overview

The primary objective of this application is to provide a platform where users can converse with a generative AI model. The application is built using popular Python libraries and packages for creating web applications, including:

- **python-dotenv**: For managing environment variables in Python applications, allowing the loading of configuration settings (e.g., API keys) from a `.env` file.
- **google-generativeai**: Used to interact with Google’s Generative AI services, specifically the Google Gemini Pro AI. It provides a Python interface to access and utilize various generative AI capabilities offered by Google.
- **streamlit**: Used to create interactive, web-based applications in Python, allowing rapid development and deployment of data-driven applications with easy-to-modify visualizations.

This system represents a sophisticated web application designed to facilitate interactions with a generative AI model, specifically Google’s Gemini Pro, using the Streamlit framework. The application demonstrates seamless integration of environment variables, AI configuration, and user interface elements to create a functional and engaging user experience.

## ♡ Features

- **Secure API Key Management**: The Google API key is securely retrieved from environment variables using the `os.getenv` method.
- **Generative AI Integration**: The Google Gemini Pro AI model is configured with the retrieved API key, enabling the application to send user queries to the AI and receive generated responses.
- **Interactive Chat Interface**: The application initializes a chat session within Streamlit, rendering the chat history on the page to enhance conversational flow.
- **User Input Handling**: An input field is provided for users to enter their queries. Once a user submits a prompt, the application handles the message by displaying it in the chat interface and sending it to the AI model. The AI’s response is then displayed, completing the interaction loop.

## ❀ Conclusion
This application exemplifies the effective use of Streamlit for creating interactive web applications that leverage advanced AI models. By integrating Google’s Gemini Pro with a user-friendly interface, it ensures secure API key management and seamless session handling, resulting in a robust and engaging user experience. This project not only showcases the potential of generative AI in creating dynamic content but also highlights the importance of good software design practices in developing web applications.

## ⟢ Links
- **Streamlit Application**: https://createcontentwithgenaibyroanjagunap.streamlit.app/
- **Github Repository**: https://github.com/Raiajgnp/CCS-229-Intelligent-System-Final-Project-by-Roan-Jagunap

